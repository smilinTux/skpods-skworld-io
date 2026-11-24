# skpods-skworld-io

Landing site for **SKPods** (Solid pods with an AI guardian), served at
**[skpods.skworld.io](https://skpods.skworld.io)** by GitHub Pages.

- **Product repo:** https://github.com/smilinTux/skpods
- **Deploy role:** https://github.com/smilinTux/skstacks/tree/main/v1/ansible/optional/skpods
- **Ecosystem:** https://skworld.io

## Files

| File | Purpose |
|------|---------|
| `index.html` | The landing page (self-contained CSS, no build) |
| `docs.html` | Live viewer for `smilinTux/skpods` `docs/*.md` |
| `docs-manifest.json` | Offline fallback for the viewer, refreshed daily by a workflow |
| `assets/` | Screenshots and the Guardian demo video, copied from `skpods/showcase/apps/*/docs/` |
| `og.png` | 1200x630 social card |
| `CNAME`, `robots.txt`, `sitemap.xml`, `llms.txt` | Pages domain, crawler signals, sitemap, LLM summary |

Built to the SKWorld site standard, using the skworld.io type and colour system. Apache-2.0.
