# Shiva Sridhar M — Personal Portfolio 🚀

An immersive, design-driven portfolio website displaying engineering projects, build logs, and professional certifications. Built with React (standalone in-browser compilation), Tailwind CSS, GSAP, and Lenis Smooth Scroll.

---

## 🛠️ Tech Stack & Architecture

- **Core**: HTML5, React 18, Babel Standalone (for in-browser parsing)
- **Styling**: Tailwind CSS (loaded via CDN)
- **Animations**: GSAP (GreenSock Animation Platform) & ScrollTrigger
- **Smooth Scroll**: Lenis Scroll
- **Local Server**: Node.js HTTP Server (`server.js`) using built-in modules (`http`, `fs`, `path`)

---

## 🚀 Easy Deployment Options

Since this is a frontend-centric application served by a minimal Node.js script, you have two primary deployment pathways:

### Option 1: Static Hosting (Recommended & 100% Free)
Since the entire application runs in the client browser (`index.html`) using CDNs for dependencies, you do not need an active Node.js server running in production. Hosting it as a static site offers **instant loading times**, **zero maintenance**, and is **completely free**.

#### 1.1 Deploying to GitHub Pages (Easiest)
Since your project is already pushed to GitHub, you can host it directly using GitHub Pages in under a minute:
1. Go to your repository settings: [shivasridhar/PORTFOLIO](https://github.com/shivasridhar/PORTFOLIO/settings).
2. Scroll down the left sidebar and click on **Pages** (under the **Code and automation** section).
3. Under **Build and deployment**:
   - **Source**: Select `Deploy from a branch`.
   - **Branch**: Select `main` and set the folder to `/ (root)`.
4. Click **Save**.
5. Wait 1–2 minutes. Refresh the settings page, and your live URL will be shown at the top (e.g., `https://shivasridhar.github.io/PORTFOLIO/`).

> [!TIP]
> This is the recommended choice if you want to host your portfolio directly off your GitHub repository without signing up for external hosting services.

#### 1.2 Deploying to Vercel
1. Go to [Vercel](https://vercel.com/) and log in with your GitHub account.
2. Click **Add New...** > **Project**.
3. Import the `PORTFOLIO` repository.
4. Keep all default configurations (Vercel automatically detects the `index.html` file).
5. Click **Deploy**. Your site will be live on a custom `vercel.app` subdomain immediately.

#### 1.3 Deploying to Netlify
1. Go to [Netlify](https://www.netlify.com/) and log in.
2. Select **Add new site** > **Import an existing project**.
3. Connect your GitHub account and select the `PORTFOLIO` repository.
4. Click **Deploy portfolio**.

---

### Option 2: Full-Stack Node.js Hosting
If you explicitly want to run your custom [server.js](file:///d:/PORTFOLIO/server.js) Node.js server, you can host it on platforms that support Node environments.

#### 2.1 Deploying to Render (Free Tier)
1. Go to [Render](https://render.com/) and log in using GitHub.
2. Click **New +** > **Web Service**.
3. Select your `PORTFOLIO` repository.
4. In the configuration settings:
   - **Name**: `portfolio-shiva`
   - **Language**: `Node`
   - **Build Command**: Leave empty or enter `npm install` (none needed)
   - **Start Command**: `node server.js`
5. Select the **Free Instance** type.
6. Click **Deploy Web Service**.

#### 2.2 Deploying to Railway
1. Sign in to [Railway](https://railway.app/) using GitHub.
2. Click **New Project** > **Deploy from GitHub repo**.
3. Select your `PORTFOLIO` repository.
4. Railway will automatically provision a container, run the start command (`node server.js`), and provide a public URL.

---

## 💻 Running the Project Locally

To test or run the local Node.js server:

1. Clone or navigate to the repository directory:
   ```bash
   cd PORTFOLIO
   ```
2. Start the local HTTP server:
   ```bash
   node server.js
   ```
3. Open your browser and go to:
   ```
   http://localhost:3000
   ```
