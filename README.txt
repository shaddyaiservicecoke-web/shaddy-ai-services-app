SHADDY AI SERVICES - PWA PACKAGE

Files:
- index.html: current Shaddy AI Services website with PWA links
- manifest.webmanifest: install name, theme and app icons
- sw.js: basic offline cache for the app shell
- icons/: Android app icons (192px and 512px)

Deploy the CONTENTS of this folder to the root of your website (the index.html must be at the root).
The site must be served over HTTPS for installation and service workers.

After deployment on Android Chrome:
1. Open the website using Chrome.
2. Tap the three-dot menu.
3. Choose Install app (or Add to Home screen if that is the offered option).
4. Confirm installation.

Note: this is an installable PWA, not a Google Play Store listing. External services such as WhatsApp and the website chatbot need an internet connection.
