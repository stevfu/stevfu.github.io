# stevfu.github.io

Personal website hosted on GitHub Pages.

## Quick Start (GitHub Pages)

This repository name already matches a user site format (`<username>.github.io`), so your site can be published directly from the `main` branch.

1. Push this repository to GitHub.
2. Open repository Settings -> Pages.
3. Under Build and deployment:
	- Source: Deploy from a branch
	- Branch: `main`
	- Folder: `/ (root)`
4. Save.
5. Wait about 1-3 minutes, then open your site URL:
	- `https://stevfu.github.io/`

## Local Preview

Option 1: Double-click `index.html`.

Option 2 (recommended): run a local server from this folder.

```powershell
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Files

- `index.html` - homepage overview
- `projects.html` - detailed project portfolio
- `experience.html` - professional experience timeline
- `volunteering.html` - volunteering and leadership work
- `styles.css` - site styling
- `script.js` - small UI behavior (copyright year)
- `assets/` - local images and media
- `.nojekyll` - bypasses Jekyll processing on GitHub Pages

## Migrating From Google Sites

Google Sites content is not exported as editable HTML/CSS in a way that maps cleanly to GitHub Pages, so migration is usually manual.

Recommended process:

1. Copy your text content page-by-page into `index.html`, `projects.html`, `experience.html`, and `volunteering.html`.
2. Download images/files from Google Sites and add them to the `assets/` subfolders.
3. Follow `assets/README.md` for expected image filenames.
4. Update contact/social links and email address.
5. Commit and push changes.

## Next Improvements

- Add `assets/` for profile image and project screenshots.
- Split sections into pages (`about.html`, `projects.html`, `contact.html`) when content grows.
- Add a custom domain later using a `CNAME` file.
