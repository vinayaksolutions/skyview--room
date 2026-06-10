# ✦ SkyView — Live Night Sky

A lightweight, single-file browser app that shows the exact night sky above you, right now.
No installation. No account. No telescope needed.

## What it shows
- 🪐 All 8 planets + the Moon & Sun — real positions calculated from orbital mechanics
- ⭐ 35+ named stars — Sirius, Betelgeuse, Vega, Orion's Belt, Polaris and more
- 🌫️ Deep sky objects — Orion Nebula, Pleiades, Hyades cluster
- 〰️ Constellation lines — Orion, Big Dipper, and more

## Features
- 📍 Uses your GPS for a sky that matches exactly where you are on Earth
- 🕐 Updates in real time — watch objects drift as Earth rotates
- 👆 Tap any star or planet to identify it and read a fact
- 🌐 Drag to look in any direction · Pinch/scroll to zoom
- ⛶ Full-screen mode — project it on a wall or ceiling

## How to use
Just open index.html in any browser — or visit the live GitHub Pages link.
Allow location access for maximum accuracy. Works offline after first load.

## Projection tip
Open full-screen → mirror your phone to a mini LED projector (Portronics/Zebronics, ~₹3000) 
→ point at your ceiling in a dark room → instant bedroom planetarium.

## Tech
Pure HTML + Canvas + JavaScript. Zero dependencies. Zero backend.
Astronomical math: VSOP87 (truncated), GMST/LST sidereal time, equatorial-to-horizontal coordinate transform.

## Accuracy note
Planet positions are accurate to within ~1–2° for casual observation.
For professional-grade ephemeris, use JPL Horizons or Stellarium.
