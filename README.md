# Lumina Scents — Demo E-Commerce Site

A beautiful, fully client-side e-commerce demo for fragrances and scented candles.

## Features

- Elegant product catalog (perfumes, candles, gift sets)
- Category filters
- Shopping cart with localStorage persistence
- Simulated checkout (no real payments)
- **Invoice page** — generated after order with Print / Save PDF support
- Social hub page with QR code linking to:
  - Instagram
  - X / Twitter
  - TikTok
  - Facebook
  - WhatsApp
- Fully responsive

## How to run

Simply open `index.html` in a modern browser.

Or serve the folder with any static server:

```bash
# Python
python -m http.server 8000

# Node (if you have npx)
npx serve .
```

Then visit http://localhost:8000

## Notes

- All social links are placeholders (`@luminascents` style). Replace with real URLs.
- The QR code on the Socials page encodes the current page URL so scanning it on a phone opens the social hub.
- Checkout is simulated — card details are pre-filled for demo convenience and nothing is sent anywhere.
- Cart state is saved in the browser’s localStorage.

## Customization

- Products live in `js/products.js`
- Colors and fonts are defined via Tailwind config in the HTML `<head>`
- Brand name: **Lumina Scents**
