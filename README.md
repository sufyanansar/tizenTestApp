# Tizen YouTube App

Minimal Tizen BREW web app scaffold that loads `https://www.youtube.com` in the app view.

## Files

- `config.xml` — Tizen app manifest
- `index.html` — app entry page with a full-screen iframe
- `package.json` — helper scripts for `tizenbrew`

## Usage

1. Install Tizen BREW and the Tizen SDK if needed.
2. Run `npm install` if you want to manage package scripts.
3. Use `npm start` or `tizenbrew run` to launch the app in the Tizen emulator.
4. Use `npm run build` or `tizenbrew package` to create a package.

> Note: YouTube may block rendering inside a standard iframe depending on device and browser restrictions. If that happens, use a native Tizen webview or the browser app instead.
