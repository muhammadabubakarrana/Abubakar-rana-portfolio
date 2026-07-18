# Hafiz Abubakar — Portfolio

A single-page portfolio site. Plain HTML/CSS/JS, no build step — works as-is on GitHub Pages.

## Files

- `index.html` — all page content
- `styles.css` — design tokens and layout
- `script.js` — nav behavior, mobile menu, scroll-reveal animation

## Publish it on GitHub Pages (free)

1. Create a new **public** repo on GitHub — e.g. `portfolio` (or `yourusername.github.io` if you want it at the root of your GitHub domain).
2. Upload `index.html`, `styles.css`, and `script.js` to the repo root (drag-and-drop on github.com works, or via git):
   ```bash
   git init
   git add .
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Build and deployment → Source → Deploy from a branch**, pick `main` and `/ (root)`, then Save.
4. Wait a minute or two — your site goes live at:
   - `https://YOUR_USERNAME.github.io/YOUR_REPO/`, or
   - `https://YOUR_USERNAME.github.io/` if the repo is named `YOUR_USERNAME.github.io`

## Before you publish, update these two spots

- In `index.html`, the **GitHub button** in the Contact section currently points to `https://github.com/` — replace with your actual profile URL.
- The **Portable Toilet Management** and **Fuse** project cards are marked "Private client release" since no public store links were in your CV — swap in real links if you have them, or remove the cards if you'd rather only show public apps.

## Customizing

All colors, fonts, and spacing are defined as CSS custom properties at the top of `styles.css` (the `:root` block) — change a value there and it updates everywhere.
