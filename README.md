# Shaklee Shop (Static Site)

A simple static website for a Shaklee distributor. Built with plain HTML/CSS and a JSON product list.

## How to use
1. Put your images in `assets/img/`. You can reuse `placeholder-shaklee.png`.
2. Edit `products.json` to add/remove products.
3. Open `products.html` in your browser to test locally.

## Deploy on GitHub Pages
1. Create a new GitHub repo, e.g. `shaklee-shop-site`.
2. Upload all files/folders at the root of the repo.
3. In **Settings → Pages**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`) / root
4. Your site will appear at the link shown on the Pages screen.

## Tips
- Replace `hero.jpg`, `about.jpg`, `contact.jpg` with real images.
- The grid has search + filter (Promotion / Out of Stock / In Stock).
- Product images default to `assets/img/placeholder-shaklee.png` if a file is missing.
