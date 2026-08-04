# AtmosphereX — Living Weather Window

A single-file, dependency-free weather dashboard that doesn't just show the forecast — it becomes it. The UI, colors, background scene, and ambient sound all shift in real time to match the live weather at your location.

**Design & Development — Toofan**

## Features

- 🌈 Neon, weather-reactive color themes (golden sunny, electric-blue rain, violet thunderstorms, icy snow, deep-purple night) with a dark/light mode toggle
- 🌧️ Living canvas background — real particle effects for rain, snow, fog, drifting clouds, twinkling stars, sun glow
- ⚡ Lightning strikes flash the entire UI and trigger a synced thunder rumble
- ❄️ Snow builds up as frost on every card; rain adds a wet-glass sheen over the UI
- 🔊 Procedural ambient sound per condition — patter of rain, thunder rumble, hushed snow, a cheerful sunny bell loop, and night crickets (Web Audio API, no audio files)
- 📍 Auto geolocation with graceful fallback + city search with autocomplete
- 📊 Live data: current conditions, 24h hourly forecast, 7-day outlook, UV, AQI, sunrise/sunset, moon phase, animated trend charts
- 🌡️ °C / °F toggle, fully responsive, works offline-friendly as a single static file

## Tech

Vanilla HTML/CSS/JS — no build step, no framework, no API key required.
Weather data: [Open-Meteo](https://open-meteo.com/) · Reverse geocoding: [BigDataCloud](https://www.bigdatacloud.com/)

## Run it

Just open `index.html` in any modern browser. That's it.

## Deploy for free (GitHub Pages)

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under "Build and deployment", set **Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Save — your live link will appear at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## License

Free to use, modify, and share.
