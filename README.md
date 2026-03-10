# Quarto Reveal.js Presentation

This repository is configured to build a Quarto Reveal.js slide deck and deploy it to GitHub Pages.

## Files

- `_quarto.yml`: Quarto project config
- `index.qmd`: your presentation source
- `.github/workflows/deploy-pages.yml`: GitHub Actions workflow for build + deploy

## Use It Locally

1. Install Quarto: <https://quarto.org/docs/get-started/>
2. Run a live preview:

```bash
quarto preview
```

3. Build the static output:

```bash
quarto render
```

Rendered files are generated in `_site/`.

## Publish to GitHub Pages

1. Push this repository to GitHub.
2. In your repo settings, go to `Pages`.
3. Set `Source` to `GitHub Actions`.
4. Push to `master` (or run the workflow manually).

After deployment, your slides will be available at your GitHub Pages URL.
