# Mr.Zinger PWA

## Files
- `index.html` — food menu, cart, checkout, WhatsApp ordering, order history and local admin menu editor
- `manifest.json` — installable PWA settings
- `sw.js` — basic offline app shell caching
- `icon.svg` — app icon

## Publish free with GitHub Pages
1. Create a new public GitHub repository named `mrzinger`.
2. Upload all four files from this ZIP to the repository root (not inside another folder).
3. Open repository Settings → Pages.
4. Under Build and deployment, choose Deploy from a branch → `main` → `/ (root)` → Save.
5. Wait for the Pages link, then open it on Android Chrome.
6. Chrome menu (⋮) → Install app / Add to Home screen.

## Important settings
- WhatsApp number configured: `03222775671` (international format in code)
- Delivery area: Keamari, Karachi
- Delivery fee: Rs. 150 (matching the pasted checkout code)
- Admin PIN: `1234` (change `ADMIN_PIN` in `index.html` before publishing)

## Notes
- Orders open WhatsApp for customer confirmation. The order history and menu edits are stored in that browser/device only; they are not synced between phones.
- Online payment is shown as a selection only; no payment gateway is connected.
- This is a PWA website, not a Play Store APK.
- The menu and order data can be exported from the admin panel. To open Admin Panel, press Ctrl+Shift+A on a keyboard; on mobile, use a browser bookmarklet or temporarily add `openAdmin()` to a button in `index.html`.
