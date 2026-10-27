# NIGHTSHIFT — Interactive Lively Wallpaper

A responsive cyberpunk desktop scene inspired by the developer/musician workspace concept. Built with plain HTML, CSS and JavaScript; no build step or framework required.

## Install in Lively Wallpaper
1. Open the repository and choose **Code → Download ZIP**.
2. Extract the downloaded ZIP.
3. Open **Lively Wallpaper**, click **Add Wallpaper (+)**, and browse to the extracted `index.html`.
4. Select it and set it as your wallpaper.

## Interactive features
- **VS Code / Browser / Files / Music:** opens the associated web destination.
- **Settings:** toggle subtle motion, hide the system display, dim the scene, or change accent colour.
- **Next Up:** interactive checklist, completion counter and reset button.
- **Player:** visual play/pause state, next/previous track selection, shuffle and favourites.
- **Clock:** local time and date update automatically.

## Important limitations
- The music player is a **UI simulation** and does not play audio. Use the Music shortcut to open Spotify.
- CPU/GPU/RAM/temperature figures are decorative estimates, not live telemetry. Browser wallpapers cannot read those hardware sensors directly without an external integration.
- Google Fonts is optional styling; system-font fallbacks are provided for offline use.

## Files
- `index.html` — layout and controls
- `style.css` — responsive neon/glass UI and CSS-generated night skyline
- `script.js` — click actions, clock, checklist, settings and player state
- `LivelyInfo.json` — Lively wallpaper metadata

## Performance choices
No canvas particle engine, video background or animation-heavy framework. Motion is limited to a cursor blink, small UI transitions and decorative telemetry updates. The motion can be disabled from Settings.
