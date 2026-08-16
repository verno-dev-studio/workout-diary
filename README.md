# Workout Diary — Map-Based Tracker

<p><a href="https://verno-dev-studio.github.io/workout-diary/"><b>&#9654; Live demo</b></a> &nbsp;&middot;&nbsp; <a href="https://github.com/verno-dev-studio/workout-diary">Source</a></p>

## Overview

A Mapty-style workout logger: click anywhere on an interactive map to record a running or cycling session. Each workout is pinned with a custom marker and popup, listed in the sidebar, and persisted in the browser so it survives reloads.

## ✨ Features

- Click the map to log a workout at that exact location
- Running and cycling types with type-specific fields (pace / speed, cadence / elevation)
- Interactive Leaflet map with custom markers and popups
- Geolocation to centre the map on the user
- Workout list synced with map markers — click to pan
- Persistent storage via localStorage
- Object-oriented architecture (App, Workout, Running, Cycling classes)

## 🛠️ Tech stack

- **JavaScript (ES6 classes)** — OOP architecture and app logic
- **Leaflet** — Interactive maps and markers
- **Geolocation API** — Locating the user
- **localStorage** — Persisting workouts between sessions
- **Sass** — Styles

## 🚀 Getting started

No build step or dependencies. Clone the repo and open `index.html` in any modern browser, or serve the folder with a static server:

```bash
npx serve .
```

---
<sub>Portfolio demo. Map tiles © OpenStreetMap contributors.</sub>
