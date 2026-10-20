# hootle.suhi.app

Landing page for Hootle, a Mac menu bar owl that keeps your Mac awake. A Suhi app.

Static pages, no build step: `index.html` (landing), `privacy/` (privacy policy) and `support/` (help and contact), with icons in `assets/`. Served by GitHub Pages from `main` at the repo root; the custom domain is set in `CNAME`.

The privacy and support pages are the URLs used in App Store Connect:

- Privacy Policy URL: https://hootle.suhi.app/privacy/
- Support URL: https://hootle.suhi.app/support/
- Marketing URL: https://hootle.suhi.app/

To preview locally:

```bash
python3 -m http.server 8000
```
