# robwuebker.github.io

Static GitHub Pages site for Rob Wuebker.

## Source Of Truth

Edit `index.html` directly on `main`. Supporting assets such as `profile.png` and the Google verification file live in the repository root.

## Local Preview

```bash
python3 -m http.server 8123
```

Then open `http://localhost:8123/`.

## Deployment

Push changes to `main`. GitHub Pages serves the repository root from `main`; verify the GitHub-managed `pages build and deployment` run and then check the live site.

No Notion, Loconotion, or generated-site step is required.
