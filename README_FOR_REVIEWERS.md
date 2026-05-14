# Global Life-Income Atlas Review Site

This folder is a generated static website for informal researcher review.

Open `index.html` through a static host such as Netlify, GitHub Pages, or
Cloudflare Pages. Direct `file://` opening is not the supported route because
browser security rules can block local CSV/GeoJSON loading.

Reviewer notes:
- The atlas is a research preview, not a final public release.
- Missing values are left missing rather than filled silently.
- The Methods section includes the source comparability disclosure.
- The Overview section links to the downloadable national country-year dataset.

Maintainer note:
- Do not edit this folder by hand.
- Rebuild it from the repository root with:
  `python3 scripts/build_share_site.py --root .`
