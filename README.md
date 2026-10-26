# Hajiyar Hotel Website

A responsive, modern restaurant/hotel website concept built with plain HTML, CSS and JavaScript. The visual style uses soft green tones, warm neutrals, glassmorphism panels, subtle motion and hover interactions.

## Files
- `index.html` — page structure and sections
- `css/style.css` — visual design, responsive layouts and animations
- `js/script.js` — menu data, search, category filters, mobile navigation, reveal effects and back-to-top control
- `assets/` — place your own downloaded/local images here if preferred (currently the sample site uses remote Unsplash image URLs)

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser. For the most reliable local development experience, use VS Code with the Live Server extension.
3. Internet access is needed for the remote sample photos, Google Fonts, Lucide icons and embedded map.

## Important customization before publishing
1. **Menu:** Update the `menuItems` array in `js/script.js` with the hotel's real dishes, descriptions, prices, categories and image URLs.
2. **Food photos:** Replace sample Unsplash images with real photographs of Hajiyar Hotel's actual dishes. For local files, put images in `assets/` and set each item's image to a path such as `assets/chicken-biryani.jpg`.
3. **Contact details:** In `index.html`, replace the placeholder address, phone number, call link, opening hours and Google Maps embed with the hotel's actual information.
4. **Reviews:** The current customer reviews are clearly sample copy. Replace them with genuine customer feedback and get permission to publish names/photos.
5. **Branding:** Update colors, logo mark and text if you have a real logo.
6. **Domain and hosting:** Upload the files to a static host such as GitHub Pages, Netlify or your hosting provider. This static website does not include a database, online ordering, reservations, or a review-submission backend.

## Notes
- Menu search checks dish names, categories, tags and descriptions.
- The menu category filters work together with search.
- The map currently points to Colombo, Sri Lanka as a placeholder. Set it to the exact hotel location before launch.
- Sample prices are placeholders only and should be verified before publication.
