# SocialChat — Chat Studio

A mobile-friendly, front-end chat simulator built with HTML, CSS and JavaScript.

## Features
- Create, edit and save multiple local profiles (name, ID, bio and profile photo).
- Create two-sided conversations and switch the sending identity.
- Messenger-, TikTok-, WhatsApp- and Instagram-inspired visual themes.
- Upload a custom photo wallpaper for each conversation or set a default wallpaper.
- Send text, emoji and image messages.
- Local chat history saved in browser LocalStorage.
- Export a JSON backup of profiles, conversations and settings.
- Responsive layout for Android/mobile and desktop browsers.

## Run on Android / Acode
1. Extract the ZIP.
2. Open the `SocialChat` folder in Acode.
3. Open `index.html` with Acode Preview or a browser.
4. Create profiles, then tap **New chat**.

## Important limitations
- This is a local same-device chat simulator. It does not send messages over the internet or connect real Messenger/TikTok/WhatsApp/Instagram accounts.
- For two separate phones to chat live, a backend/database and authentication are required.
- Data is stored in this browser on this device. Browser storage can be cleared by the user or operating system; use **Export backup (JSON)** regularly.
- Uploaded photos are resized/compressed in the browser before saving to help control storage use.
- This version does not yet include a dedicated HD screenshot export tool. Browser screenshots can be used for now; a dedicated high-resolution chat export can be added as a next build.

## Files
- `index.html` — app structure and dialogs
- `style.css` — responsive layout and themes
- `app.js` — profiles, chats, wallpaper, local storage and interactions
