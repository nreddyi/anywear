# Anywear – Our Story (Aurora) for Shopify

Each section of the Aurora design is its own Shopify section file. Every section has its own styles and script built in, and everything is editable in the theme editor.

## Files

| File | Section |
|---|---|
| `sections/aw-aurora-background.liquid` | Soft moving colour background (keep it first on the page) |
| `sections/aw-story-hero.liquid` | Hero with 4 floating photo cards and badges |
| `sections/aw-story-moments.liquid` | "Three moments" swipeable story panels |
| `sections/aw-story-values.liquid` | Comfort / Fit / Colour tilt cards |
| `sections/aw-story-day.liquid` | "A day in Anywear" fan of cards |
| `sections/aw-story-founder.liquid` | Founder note with colour ring portrait and full letter |
| `sections/aw-story-mission-vision.liquid` | Mission and Vision cards |
| `sections/aw-story-reviews.liquid` | Reviews as chat bubbles |
| `templates/page.our-story.json` | Page template with all sections in order and content filled in |

## Install

1. In Shopify admin, go to **Online Store → Themes → … → Edit code**. Duplicate the theme first if you want to stay safe.
2. Under **Sections**, click **Add a new section**, give it the same name as the file (for example `aw-story-hero`), and paste in the file's contents. Do this for all 8 files.
3. Under **Templates**, click **Add a new template**, choose type **page** and **JSON**, name it `our-story`, and paste in `page.our-story.json`.
4. Go to **Online Store → Pages → Our Story** and set **Theme template** to `our-story`. Save.
5. Open the page in **Customize** to change text and photos.

## Photos

Each photo has an **image picker** and an **image URL** box. The URL boxes are pre-filled with the current anywearindia.com photos, so the page looks right straight away. Choose an image in the picker to replace a photo; the picker always takes priority over the URL.

## Notes

- Uses only the Poppins font, loaded from Google Fonts.
- Your theme's own header and footer are used.
- The founder name is still `[Founder Name]`. Change it in the "Story: founder note" section.
- The founder portrait is zoomed into the current photo (155%). If you upload a ready-cropped portrait, set **Portrait zoom** to 100%.
