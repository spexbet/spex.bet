# Spex site

Static site on GitHub Pages. **Paused as of 2026-10-15**: development and distribution are on hold.

What is live:

| File | Purpose |
|---|---|
| `index.html` | The one public page: "paused" notice |
| `404.html` | Same notice, so old links (`/glance/`, `/ios/`, `/privacy.html`) land on it |
| `glance/appcast.xml` | Empty Sparkle feed. Installed copies check here and are told they're up to date; nothing is offered |
| `assets/app-icon.png`, `assets/fonts/` | Icon and Space Grotesk (OFL) |
| `CNAME` | Custom domain |

The previous product pages, screenshots and version stamping live in git history (last full-site commit: `ace00e0`).

Deploy: push to `main`; the `Deploy site` workflow publishes the repo as-is.
