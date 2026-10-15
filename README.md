# CarStudio

One landmark car per decade, 1924 to 2020, as real 3D models scaled to factory dimensions, with blueprint sheets drawn from the model geometry.

Live: https://carstudio-mocha.vercel.app

## Run locally
Any static server works, e.g. `python3 -m http.server` in this folder, then open http://localhost:8000.

## Contents
- `index.html` – viewer (model-viewer, self-hosted in `vendor/`, fonts in `fonts/`)
- `cars.js` / `cars.json` – specs, factory dimensions, model credits
- `models/` – Draco-compressed GLBs
- `blueprints/` – blueprint sheets rendered from each model
- `concept/` – AI concept art (not to scale)

## Model credits and licenses
Each 3D model is by its Sketchfab author under the license listed in `cars.json` (CC BY, CC BY-NC, CC BY-NC-SA, or Sketchfab Standard). Several are non-commercial; keep this repo private and the site non-commercial unless those models are replaced.
