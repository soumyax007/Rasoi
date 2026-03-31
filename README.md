# Rasoi – Indian Recipes Website
### Web Development Assignment | Soumya | South Asian University

---

## Project Structure

```
recipe-website/
├── index.html          ← Home page
├── recipe1.html        ← Butter Chicken
├── recipe2.html        ← Dal Makhani
├── recipe3.html        ← Hyderabadi Biryani
├── recipe4.html        ← Palak Paneer
├── recipe5.html        ← Gulab Jamun
├── css/
│   └── styles.css      ← All styles (single file)
└── images/             ← Place downloaded images here (see below)
```

---

## Images to Download

The site currently uses Unsplash URLs (works online). For the submission ZIP,
download these free images and save them in the `images/` folder:

| File name to save as      | Download from                                                        |
|---------------------------|----------------------------------------------------------------------|
| `butter-chicken.jpg`      | https://unsplash.com/photos/ZqHCpxhMECo (search "butter chicken")   |
| `dal-makhani.jpg`         | https://unsplash.com/photos/NzHRSLhc6Cs (search "dal makhani")      |
| `biryani.jpg`             | https://unsplash.com/photos/ayz9rDIEFYg (search "biryani")          |
| `palak-paneer.jpg`        | https://unsplash.com/photos/EaB4Ml7C7fE (search "palak paneer")     |
| `gulab-jamun.jpg`         | https://unsplash.com/photos/mj0JxH2l-g0 (search "gulab jamun")      |

All Unsplash images are free to use — no attribution required by their licence.

After downloading, update the `src` attributes in each HTML file from the
Unsplash URL to the local path, e.g.:

```html
<!-- before (online) -->
<img src="https://images.unsplash.com/photo-1603894584373-5ac82b2ae398?w=600&q=80" ... />

<!-- after (local) -->
<img src="images/butter-chicken.jpg" ... />
```

---

## Features Implemented

- 1 Home page + 5 Recipe pages (7 HTML files total)
- Single shared CSS file
- Day / Night mode toggle — persists across all pages via `localStorage`
- Desktop navbar with hover underline effect
- Mobile hamburger menu (CSS-only checkbox trick — no JavaScript)
- Flexbox layout throughout; CSS Grid for the recipe cards
- Hover animations on cards (lift + image zoom)
- Responsive media queries for desktop and mobile
- Search bar UI (visual only, as required)
- Category filter buttons (UI only)
- Sticky navbar
- Semantic HTML (`<nav>`, `<main>`, `<aside>`, `<article>`, `<footer>`)
- Clean, consistent footer on every page with GitHub link placeholder

---

## Deployment (GitHub Pages)

1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages → Source → main branch / root**.
3. GitHub will provide a live URL like `https://username.github.io/recipe-website/`.

---

*Made by Soumya — South Asian University*
