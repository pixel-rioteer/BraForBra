# BraForBra

A simple, supportive educational website about bra and underwear styles, comfort, body changes and periods.

## Features
- Browse explanations of common bra styles and underwear styles.
- Simple abstract garment diagrams.
- Record period start dates in a browser-only diary.
- See a rough average-cycle estimate after recording at least two dates.
- Remove individual dates or clear all dates.
- Responsive layout for mobile and desktop.

## Run locally
No build tools or dependencies are required. Clone/download the repository and open `index.html` in a modern browser. Alternatively run `python -m http.server 8000` and visit `http://localhost:8000`.

## Privacy and safety
The period diary uses browser `localStorage`; dates are not sent to a server. Anyone using the same browser profile may be able to view them. Avoid entering private information on a shared device. Clearing browser site data may erase the diary.

Cycle estimates are approximate and are not medical advice or a contraception method. This site is educational; speak with a trusted adult, school nurse or healthcare professional if something is worrying you.

Garment diagrams are abstract illustrations. The planned preview concept is limited to illustrated clothing forms, not camera-based body scanning or realistic try-on of underwear.

## Deploy with GitHub Pages
1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`, then save.
4. GitHub Pages will display the published URL in the Pages settings.

## Future improvements
- More detailed accessible garment diagrams.
- Optional cycle-length settings and clearer uncertainty ranges.
- A garment comparison page and additional sizing/fit education.
- An illustrated, non-photographic style preview.
