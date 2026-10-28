# 1xBit Bangladesh — Cloudflare Workers Static Assets

This repository is ready for GitHub-connected Cloudflare Workers Builds.

Settings: Build command = blank; Deploy command = `npx wrangler deploy`; Root directory = `/`; Production branch = `main`.

Static website files are in `public/`. The `wrangler.jsonc` config points Workers Static Assets at that directory.

For a Cloudflare Pages project instead, use the contents of `public/` as the site root (Pages build output directory `public`).
