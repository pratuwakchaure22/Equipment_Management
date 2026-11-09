# SMART LAB — Research-style Equipment Portal

Static HTML, CSS and JavaScript. The inventory and equipment photos are bundled and available immediately in local demo mode.

## Preview
Open `index.html` in Chrome, or upload the whole folder to GitHub Pages.

## GitHub Pages
Upload all files/folders to the root of a GitHub repository. Set Settings → Pages → Deploy from branch → main → / (root). All asset paths are relative, so project-site URLs are supported.

## Live multi-device transactions
The website needs Firebase Authentication and Firestore for shared records. Populate `firebase-config.js`, follow Firebase setup in the previous deployment instructions, configure Firestore rules from `firestore.rules`, enable authentication and import seed records. GitHub Pages by itself serves static files and does not provide persistent shared storage. Do not deploy the demo administrator password as production security.

## Equipment photos
Original photos extracted from the user's workbook are stored in `assets/equipment`. Admin edit/add form supports photo preview, upload and replacement. Browser-only uploads persist locally to that browser; Firebase requires the corresponding configured database and rules.

## Visual design
Dark editorial research-lab style based on user's supplied SMART LAB public website screenshot. Uses deep charcoal, ultraviolet/plum panels, muted gold highlights, crest branding, and responsive layout. Existing workflows preserved.
