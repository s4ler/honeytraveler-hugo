HoneyTraveler — Reset Bundle v4.4
Generated: 2025-11-10 10:52

Restore Steps (iPad / Working Copy)
1) In Files → your repo root, delete EVERYTHING except the `.git` folder.
2) Unzip this bundle into the repo root (same level as `.git`).
3) Put the real Ananke theme files at `themes/ananke/` (overwrite placeholder).
4) Commit & push in Working Copy → GitHub. Cloudflare Pages rebuilds.
5) Replace `static/robots.txt` with your production version when ready.

Contents
- config.toml
- archetypes/ (default, page, news/post, types/honeydew-or-forest)
- static/robots.txt (staging: Disallow all)
- themes/ananke/PLACEHOLDER.txt
- Cloudflare redirect artifacts if present in this zip
