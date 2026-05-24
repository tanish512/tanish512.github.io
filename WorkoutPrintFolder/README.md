# WorkoutPrintFolder

Simple static website consisting of three files:

- `index.html` — main page and markup
- `script.js` — client-side JavaScript (app logic)
- `style.css` — styles

Quick start

1. Open `index.html` in your browser (double-click or `File → Open`).
2. Or serve locally from the project root:

```bash
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

What this app is

This is a small single-page static site. The UI and behavior are implemented in `index.html`, `script.js`, and `style.css`. Use the site directly in a browser or host it via GitHub Pages.

Deploying with GitHub Pages

1. Push this repository to GitHub.
2. In the repository Settings → Pages, set the source to the `main` branch (root). GitHub will serve the `index.html` automatically.

Notes

- This repository intentionally contains only the three app files and this README.
- If you want automatic CI/CD or artifact uploads, I can add a workflow on request (I removed the prior workflow per your instruction).
