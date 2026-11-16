# Santhosh Kumar E – Portfolio

Static portfolio site (one `index.html`, no build step) hosted with GitHub Pages.

## Deploy (user site at https://YOUR-USERNAME.github.io)

1. On GitHub, create a **public** repository named exactly `YOUR-USERNAME.github.io`.
2. Upload `index.html` and this `README.md` to the repository root (or push them with git).
3. Open **Settings → Pages**. Under *Build and deployment*, set **Source: Deploy from a branch**, branch **main**, folder **/ (root)**, then Save.
4. Wait about a minute. Your site is live at `https://YOUR-USERNAME.github.io`.

## Before publishing

Search `index.html` for `YOUR-USERNAME` and replace it with your GitHub username (3 places: two project repo links and the GitHub button).

## Git commands

```bash
git init
git add .
git commit -m "Add portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
git push -u origin main
```
