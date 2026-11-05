# James Tran · Projects

A static portfolio page (`index.html` + `styles.css`) for GitHub Pages. No build step.

## Publish at https://quantumarc.github.io

1. On GitHub, create a **public** repository named exactly `quantumArc.github.io`.
2. From this folder:
   ```sh
   git init
   git add .
   git commit -m "Add portfolio site"
   git branch -M main
   git remote add origin https://github.com/quantumArc/quantumArc.github.io.git
   git push -u origin main
   ```
3. In the repo, open **Settings → Pages** and check the source is **Deploy from a branch**, `main`, `/ (root)`.
   The site appears at https://quantumarc.github.io within a minute or two.

## Editing

- Each project is one `<article class="project">` in `index.html`. Copy one to add a project.
- `data-tags` controls the filter chips: `ai`, `web`, `mobile`, `desktop`, `3d`.
- Add your email, LinkedIn or a resume PDF in the `contact` nav near the top.
- When a repo becomes public, replace its `<span class="private">…</span>` with
  `<a href="https://github.com/quantumArc/REPO">Source</a>`.
