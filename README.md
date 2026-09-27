# SOM Engineering Calculator

## Included
- Dark / Light / System theme
- Calculation history
- Favorites
- Print / Save as PDF
- PWA install button
- Offline service worker
- Settings
- About
- Beam calculator: simply supported + cantilever, point load + full-span UDL, SFD/BMD
- Stress & strain
- Material properties
- Formula reference

## Run locally
Use a local HTTP server (not `file://`), for example:
`python -m http.server 8000`
Then open:
`http://localhost:8000/`

## Deploy
Deploy the folder to an HTTPS host such as GitHub Pages. The manifest and service worker are included so supporting browsers can offer installation.

## PDF
The PDF button uses the browser's print dialog. Choose "Save as PDF".

## Note
Material values are representative reference values and should be checked against the applicable textbook/standard before engineering design use.
