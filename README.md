# paulmerolla.com

Personal website. Plain HTML + CSS, no build step.

- `site/` – everything that gets published.
- Every push to `main` deploys `site/` to GitHub Pages via `.github/workflows/deploy.yml` (takes about a minute).

Preview locally: `python3 -m http.server -d site 8000`, then open http://localhost:8000
