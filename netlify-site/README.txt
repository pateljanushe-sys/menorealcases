# Real Life: Menopause Cases — Netlify deploy

This folder is a complete, self-contained static website. No build step, no
dependencies, nothing to install.

## Fastest way to deploy (drag & drop)

1. Go to https://app.netlify.com/drop
2. Drag this entire folder (the one containing index.html) onto the drop zone.
3. Netlify gives you a live URL in a few seconds. Done.

To use your own name, open Site settings → Domain management and either set a
Netlify subdomain (e.g. menopause-cases.netlify.app) or add a custom domain.

## Updating later

Re-export the site, then drag the new folder onto the same site's "Deploys"
tab (or use "Deploy manually"). It replaces the old version.

## Notes

- Everything (fonts, data, logic) is inlined into index.html, so it works
  offline and over any static host (Netlify, Vercel, GitHub Pages, S3, etc.).
- Learner progress and scores are saved in each visitor's own browser
  (localStorage) — nothing is sent to a server.
- EDUCATIONAL USE ONLY. Answers are drafted from current Menopause Society
  (NAMS) guidance; verify against primary sources before any clinical decision.
