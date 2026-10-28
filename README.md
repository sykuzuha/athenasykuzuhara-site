# Athena Sykuzuhara Personal Website

A modern, responsive personal website designed to deploy directly to GitHub Pages.

## Files

- `index.html` - Main page structure
- `styles.css` - Visual design and responsive layout
- `script.js` - Menu toggle, reveal animations, dynamic footer year
- `.github/workflows/deploy.yml` - Automatic GitHub Pages deployment

## Quick Customization

1. Update name, headline, and text content in `index.html`.
2. Replace social links and email in the Contact section.
3. Swap project cards with your real projects.

## Deploy on GitHub Pages

1. Create a GitHub repository and push this folder to the `main` branch.
2. In GitHub, open **Settings -> Pages**.
3. Set **Source** to **GitHub Actions**.
4. Push any change to `main`; the workflow deploys automatically.

Your site URL will look like:

`https://<your-username>.github.io/<repository-name>/`

If you want a root-domain Pages site (`https://<your-username>.github.io/`), name the repository:

`<your-username>.github.io`