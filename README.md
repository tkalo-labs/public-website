# Tkalo public website

Static one-page website for Tkalo.

## Local preview

Open `index.html` directly in a browser, or serve the repository root with any static file server.

## GitHub Pages

The site is ready to be served from the repository root. In GitHub:

1. Open **Settings → Pages**
2. Under **Build and deployment**, choose **Deploy from a branch**
3. Select **main** and **/(root)**
4. Save

GitHub will publish the page from the root-level `index.html`.

## Azure Storage static website

The same files can be uploaded directly to the Storage Account static website container (`$web`).

Set:
- Index document name: `index.html`
- Error document path: `index.html` (optional for this one-page site)

## Brand

Tkalo — Software Engineering · AI · Research
