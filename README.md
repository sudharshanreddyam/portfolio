# Sudharshan Reddyam — Portfolio

Personal portfolio site, built as a single static page (no build step) and hosted on GitHub Pages.

- `index.html` — the entire site (markup, styles, and a small amount of vanilla JS for theme toggle + active-section nav)
- `resume.pdf` — downloadable resume
- `.nojekyll` — tells GitHub Pages to serve the files as-is, skipping Jekyll processing

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Pushing to `main` is enough — GitHub Pages serves directly from this repo (configure under Settings → Pages → Deploy from branch → `main` / root, if not already set).
