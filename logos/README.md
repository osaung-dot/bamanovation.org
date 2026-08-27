# Portfolio company logos

The site loads these three files. Drop them in with exactly these names and
they appear automatically on the homepage and the portfolio page:

| File | Company |
|---|---|
| `bambite.png` | BamBite |
| `myint-myint-khin.png` | Myint Myint Khin |
| `totals.png` | Totals Inc. |

PNG with a transparent background, around 400px wide (they render at 74px
tall). SVG also works - change the extension in index.html and
portfolio.html to match.

If a file is missing the card falls back to a text wordmark, so a missing
logo degrades gracefully rather than showing a broken image. BamBite has an
extra step: it falls back to the Shopify CDN copy before the text.
