# MapConnect

[https://noobosaurus-r3x.github.io/MapConnect/](https://noobosaurus-r3x.github.io/MapConnect/)

**MapConnect** is a privacy-focused, single-page web tool for managing GPS points on an interactive map.
No backend, no data stored, no tracking.

## Features

* **Add points** – Click on the map, enter latitude/longitude, or paste coordinates/address. Geocoding powered by OpenStreetMap.
* **Edit points** – Drag markers to reposition. Rename, insert between, or remove points.
* **Path display** – Lines connect points in order. Option to close the path (round trip).
* **Live stats** – Total points, total path distance, and path status (open/closed).
* **Search** – Find locations by name or address; add result as a GPS point.
* **Export** – Download your points and stats as a JSON file (offline, local only).
* **Selection** – Select, multi-select, or bulk delete points.
* **Undo/Redo** – Full undo/redo stack for all point operations (50 steps).
* **Keyboard shortcuts**

  * <kbd>Ctrl/Cmd</kbd> + <kbd>Z</kbd>: Undo
  * <kbd>Ctrl/Cmd</kbd> + <kbd>Shift</kbd> + <kbd>Z</kbd> or <kbd>Y</kbd>: Redo
  * <kbd>Ctrl/Cmd</kbd> + <kbd>A</kbd>: Select all points
  * <kbd>Ctrl/Cmd</kbd> + <kbd>D</kbd>: Delete selected points
* **Quick Actions**

  * Add your current GPS location instantly.
  * Fit map view to all points.

## Usage

* **Add Points**:

  * Click on the map
  * Enter latitude and longitude
  * Paste coordinates or address (auto-detects format, supports geocoding)
  * Search location by name/address and add directly
* **Edit/Organize**:

  * Drag and drop in the list to reorder
  * Drag marker on map to move
  * Insert between two points
  * Select and delete single or multiple points
* **Path and Stats**:

  * Toggle "Close Path" for round trip calculations
  * Live update of total distance
* **Export**:

  * Download all points + stats as JSON

## Privacy

* Client-side only.
* No backend, no database, no external analytics.
* Geocoding requests go to OpenStreetMap Nominatim for location search.

## Stack

* [Leaflet](https://leafletjs.com/) for mapping
* [FontAwesome](https://fontawesome.com/) for icons
* [OpenStreetMap](https://www.openstreetmap.org/) for tiles and geocoding
* No build step, static HTML/CSS/JS, ready to deploy anywhere

## License

MIT

---
