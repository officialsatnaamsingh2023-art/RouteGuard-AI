# RouteGuard AI — Frontend Phase 1

A light, professional frontend for **RouteGuard AI – Smart Logistics & Risk-Aware Route Intelligence**.

## UI scope

- Public RouteGuard website
- Login UI
- Create Account UI
- Operations dashboard UI
- **OPERATIONS WORKSPACE** header and dashboard layout retained
- Route analysis UI
- My Routes UI
- Fleet UI
- Incident UI
- Alerts UI
- Reports UI
- Profile & Settings UI
- Responsive Bootstrap 5 layout
- Leaflet.js + OpenStreetMap base maps

## Intentionally not implemented

- No authentication or authorization logic
- No login/signup workflow
- No localStorage or browser sessions
- No backend API calls
- No database
- No real route calculation
- No real traffic/weather/incident data
- No AI/ML prediction
- No fake operational records
- No popup/toast messages for backend actions

All dashboard panels are empty until backend integration. The buttons and forms are UI elements only.

## Dashboard access for frontend development

Open `index.html#dashboard` to preview the dashboard directly without creating a fake login/session. The normal public website remains available at `index.html`.

## Run

Open `index.html` in a browser. Internet access is required for the Bootstrap, Google Fonts and Leaflet CDN assets.

## Later backend phase

The frontend can later be connected to Node.js/Express, authentication, MySQL/MongoDB, routing/traffic/weather services and the RouteGuard AI/ML model without redesigning the dashboard UI.
