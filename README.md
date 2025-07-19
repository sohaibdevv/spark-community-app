
# Spark Community

Spark Community is a modern, lightweight blogging platform inspired by Medium. It allows users to read, write, and engage with articles in a clean, minimalist interface. The entire application is built as a single-page application without any server-side rendering or complex build steps.

## ✨ Features

- **Read Articles**: Browse a feed of articles on the homepage.
- **Full Article View**: Click on any article to read its full content.
- **Write & Publish**: Create and publish your own stories.
- **Delete Stories**: Remove articles you've published.
- **Personalized**: The app asks for your name to personalize the experience.

## 🚀 Tech Stack

This project is built with a modern, no-build-step frontend stack:

- **Framework**: **React 19** (using Hooks for state and effects).
- **Language**: **TypeScript** for type safety.
- **Routing**: **React Router** for client-side navigation.
- **Styling**: **Tailwind CSS** (via CDN) for a utility-first CSS workflow.
- **Module Loading**: **ES Modules via Import Maps**. All dependencies (`react`, `react-dom`, etc.) are loaded directly in the browser from the `esm.sh` CDN, eliminating the need for a local build process (like Webpack or Vite).

---

## 🏃‍♂️ Running Locally

Since this project uses a no-build-step setup, you don't need to install any `node_modules`. You only need a simple local web server to serve the `index.html` file.

1.  Open your terminal in the project's root directory.
2.  Run one of the following commands:

    **If you have Python 3:**
    ```bash
    python -m http.server
    ```

    **If you have Node.js/npx:**
    ```bash
    npx serve
    ```
3.  Open your browser and navigate to the local address provided (e.g., `http://localhost:8000` or `http://localhost:3000`).

## ☁️ Manual Deployment to Netlify

Deploying this app to Netlify is incredibly simple because there are no build steps.

1.  **Log in** to your Netlify account.
2.  Navigate to the **"Sites"** section.
3.  **Drag and drop** your entire project folder directly onto the deployment area in the Netlify UI.

That's it! Netlify will automatically detect the `index.html` file and deploy your site. No build command or publish directory configuration is needed.
