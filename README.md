# Khyber Graphics

Printing and graphic design services in Peshawar.

Live website: https://khybergfx.vercel.app/

## Website files

- `khyber-graphics.html` contains the responsive page, styles, WhatsApp order form and image controls.
- `unnamed.png` is the original business logo; its original bytes are also embedded in the page.
- `assets/services/services-a.png` and `services-b.png` contain two generated illustrative views for every service.
- The image sheets use a 3-column, 4-row grid. The page shows the correct cell for each service and does not show the unused final cell.

Hover over a service card or focus its controls to see a short image shuffle. The image button also works on touchscreens and with Enter or Space. Reduced-motion preferences disable automatic shuffling and animation; the button still switches images.

The service images are illustrative examples, not photographs of completed customer orders.

## Local preview

From this repository, run `python -m http.server 8000`, then open `http://localhost:8000/khyber-graphics.html`.

## Deployment

The site is static and needs no framework, build step, backend credentials or runtime Supabase connection. Deploy `khyber-graphics.html` as `index.html` and include the `assets/services` directory. The original HTML and generated image files remain in this repository; Supabase keeps a private, self-contained HTML backup.

## Business profiles

- https://www.facebook.com/KhyberGFX/
- https://www.instagram.com/khyber_graphics/
