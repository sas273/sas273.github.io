# WCED — GitHub Pages Starter

This is a minimal, free-to-host scaffold for your **World Class Education in an Hour a Day** site.

## Quick Start
1. Create a repository on GitHub named `USERNAME.github.io` (replace with your username).
2. Upload all files from this folder to the repo root and commit.
3. Visit `https://USERNAME.github.io` to see the site (usually within 1 minute).

### Prefer a project site?
- Create any repo name, upload the files.
- In **Settings → Pages**, set Source to `Deploy from a branch`, choose `main` and `/ (root)`. Save.

## Add Lessons
- Duplicate `lessons/lesson-template.html` for each new lesson.
- Link to it from `index.html` or a grade/term hub page you create.

## Custom Domain (optional)
- Buy a domain from any registrar (e.g., Namecheap, Google Domains).
- In **Settings → Pages → Custom domain**, enter it.
- Add the provided DNS `CNAME` record at your registrar.
- Create a `CNAME` file in the repo root with your domain name (GitHub can add this automatically).

## Notes
- `.nojekyll` prevents Jekyll from processing folders (keeps everything static).
- The sample lesson file is self‑contained (inline styles) for easy copy/paste.
