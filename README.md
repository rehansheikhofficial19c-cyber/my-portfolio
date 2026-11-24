# Noorix Digital Lab — Portfolio

Static, single-page website built with HTML, CSS and vanilla JavaScript. No framework, package installation, or build step is required.

## Deploy to Cloudflare Pages

### Recommended: connect this GitHub repository

1. Open the Cloudflare dashboard and go to **Workers & Pages → Create → Pages → Connect to Git**.
2. Select the GitHub repository `rehansheikhofficial19c-cyber/my-portfolio`.
3. Use these build settings:
   - **Production branch:** `main`
   - **Framework preset:** `None`
   - **Build command:** leave empty
   - **Build output directory:** `/` (repository root)
4. Save and deploy. Cloudflare Pages will serve `index.html` directly.
5. For future updates, push commits to `main`; Cloudflare Pages will automatically rebuild and deploy.

### Important

- Keep `index.html`, `_headers`, and the `images/` folder at the repository root.
- Image paths are relative (for example, `images/t-001.jpg`); preserve the folder name and filename casing.
- The contact form opens WhatsApp; it does not submit data to a server.
- Google Fonts are loaded externally, so typography falls back to system fonts if Google Fonts are unavailable.
- No Node.js, npm install, or build command is needed.

## Local preview

Open `index.html` in a browser, or run any static file server from the repository root.
