# Daniel Lin — Portfolio
Static personal site for Daniel Lin, a December 2026 computer science new grad targeting software engineering and game/XR roles.

Open `index.html` in a browser, or serve the folder with any static file server. There is no build step and no backend.

## Local preview

```bash
python3 -m http.server 43127
```

Then visit [http://127.0.0.1:43127](http://127.0.0.1:43127).

## Host on GitHub Pages

1. Push this repo to GitHub (files stay in the repository root: `index.html`, `styles.css`, `script.js`, `favicon.svg`).
2. On GitHub, open the repository **Settings**.
3. In the sidebar, open **Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Set **Branch** to `main` and the folder to `/ (root)`.
6. Save. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` (or your custom domain, if you add one).

After the first deploy, allow a minute for the Pages URL to become active.
