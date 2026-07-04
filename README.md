# Hand Hand Coffee Website V2

A static one-page website for Hand Hand Coffee in MGV Commercial Complex, Parañaque. The page presents the café brand, drink menu, ordering details, visit information, and social links for a private preview before launch.

## Main features

- Sticky header with brand logo, section navigation, and a text-to-order call to action.
- Responsive mobile menu controlled by `script.js`.
- Hero section with café location, opening hours, payment notes, Wi-Fi note, and product imagery.
- Full drink menu with price tables, categories, extras, and best-seller labels.
- Drink gallery using local image assets.
- Pickup, curbside pickup, advance order, and village delivery information.
- SMS and phone links for ordering through `0977 400 7660`.
- Visit section with address, Google Maps directions, Facebook link, and Instagram link.
- FAQ-style details for ordering, payment, delivery, and Wi-Fi.
- Private preview banner and footer year that updates automatically.

## Technologies used

- HTML5
- CSS3
- Vanilla JavaScript
- Local image assets in `assets/`
- Google Fonts: Fredoka and DM Sans

## Project file structure

```text
hand-handv2/
|-- index.html
|-- styles.css
|-- script.js
|-- README.md
|-- .gitignore
|-- .gitattributes
`-- assets/
    |-- brand-banner.png
    |-- delivery.jpg
    |-- logo.png
    |-- marshmallow-latte.png
    |-- matcha-hojicha.png
    |-- strawberry-drink.png
    `-- strawberry-matcha.png
```

## How to open locally

No build step is required.

1. Open the project folder.
2. Double-click `index.html`, or right-click it and choose a browser.
3. The website will load directly from the local files.

Because the page uses Google Fonts, typography may look slightly different if the computer is offline.

## How to edit text

Most visible page text is in `index.html`.

- Edit menu names, prices, best-seller labels, opening hours, address, and FAQ answers directly in `index.html`.
- Edit button links such as SMS, phone, maps, Facebook, and Instagram links in the relevant `<a>` tags.
- Keep phone links in this format when changing them: `sms:+639774007660` and `tel:+639774007660`.
- After editing, refresh the browser to review the changes.

## How to replace images

Images are stored in `assets/` and referenced from `index.html`.

- To replace an image without editing HTML, use the same file name and image type as the existing asset.
- To use a different file name, place the new image in `assets/` and update the matching `src="assets/..."` value in `index.html`.
- Keep helpful `alt` text for each image so the page remains accessible.
- Recommended assets to check after replacement: logo, hero drink image, gallery images, delivery/order image, and social preview banner.

## Current launch checks and unfinished decisions

- Confirm the Brown Sugar Oat Latte price. The current page shows `145 / 170`; an older menu graphic reportedly showed `140 / 160`.
- Confirm all best-seller labels.
- Confirm delivery area, limits, and possible fees.
- Confirm public display of the phone number.
- Remove the private preview banner after written owner approval.
- Review all menu prices, hours, address, and social links before publishing.

## Beginner Git workflow

Use Git only after confirming the project files are ready.

```bash
git status
git add README.md
git commit -m "Update README"
git status
```

Before committing website changes, review the site locally in a browser and confirm the launch checks above. Push only when the owner-approved version is ready to share.
