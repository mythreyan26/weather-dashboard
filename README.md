# SkyWatch - Live Weather Dashboard

A responsive, modern weather dashboard that provides real-time weather information and a 5-day forecast for any city worldwide using the Open-Meteo API.

## Features

- **Live Weather Data**: Real-time temperature, condition description, weather emoji icons, and coordinates.
- **5-Day Forecast**: Displays daily weather icons along with daily high and low temperatures.
- **Auto City Geocoding**: Search any city worldwide powered by the Open-Meteo Geocoding API.
- **Persistent City Memory**: Automatically remembers and restores the last searched city on reload using `localStorage`.
- **Keyboard Shortcuts**: Press `Enter` to search instantly.
- **Responsive Design**: Optimized for desktop and mobile screens.
- **Zero Dependencies**: Pure HTML, CSS, and Vanilla JavaScript.

## Live Demo

Once GitHub Pages is activated, view the live application at:
`https://mythreyan26.github.io/weather-dashboard/`

## Built With

- **HTML5 & CSS3** (Vanilla)
- **Modern JavaScript** (ES6+)
- **Open-Meteo APIs**:
  - [Geocoding API](https://open-meteo.com/en/docs/geocoding-api)
  - [Weather Forecast API](https://open-meteo.com/en/docs)
- **Google Fonts** (Inter)

## Getting Started Locally

Simply open `index.html` in any modern web browser or serve it with a local web server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js npx
npx serve .
```
