# FreshCheck

FreshCheck is a responsive, static website prototype built with HTML, CSS and JavaScript.

## Project files
- `index.html` — website pages and structure
- `style.css` — colours, layout, typography and responsive styling
- `script.js` — navigation, food list, expiry tracker and interactions

## Preview locally
Open `index.html` in a browser, or use the Live Server extension in Visual Studio Code.

## Publish using GitHub Pages
1. Create a repository on GitHub, for example `freshcheck`.
2. Upload `index.html`, `style.css`, `script.js` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then save.
6. Wait for GitHub Pages to publish. Your site address will look like `https://YOUR-USERNAME.github.io/freshcheck/`.

## Prototype notes
- Food entries and profile details are stored in the visitor's browser using local storage.
- Login and sign-up screens are front-end demonstrations only; no real authentication service is connected.
- Barcode entry and label photo upload do not automatically identify products.
- Support messages are not sent to a support team.
- Recipe and food photos are loaded from Unsplash and need an internet connection.
- Date reminders are organisational aids, not food-safety checks.
