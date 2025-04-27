# 🌦️ Weatherly — The Ultimate Weather Forecast App

**Weatherly** is a sleek and responsive weather application that delivers real-time weather updates, a 5-day forecast, air quality information, and more. Built with modern web technologies and powered by the OpenWeatherMap API, Weatherly is designed to be fast, accurate, and beautifully simple.

---

## 🚀 Live Preview

🔗 [View Website Here](#https://weatherly-ksduz7mdc-shatakshigupta028s-projects.vercel.app/)  

---

## 🛠️ Built With

- **HTML5** — Structure
- **CSS3** — Styling
- **JavaScript (ES6 Modules)** — Functionality
- **OpenWeatherMap API** — Real-time weather data

---

## ✨ Features

- 🔍 **City Search** — Find weather by any city name
- 📍 **Current Location** — Get weather for your exact location
- 🕒 **Hourly Forecast** — 3-hour interval updates
- 📅 **5-Day Forecast** — Plan your week with daily highs
- 🌫️ **Air Quality Index** — Know the air you breathe
- 🌅 **Sunrise & Sunset** — Daily sunrise and sunset times
- 📱 **Responsive Design** — Works on mobile, tablet, and desktop
- ⚡ **Fast & Minimal UI** — Focused on speed and user experience

---

## 📂 Project Structure

```
weatherly/
├── index.html
├── favicon.svg
├── LICENSE
├── README.md
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   ├── api.js
│   │   ├── app.js
│   │   ├── module.js
│   │   └── route.js
│   └── images/
│       ├── logo.png
│       └── weather-icons/
```

---

## 📦 Getting Started

To run Weatherly locally:

```bash
# Clone the project
git clone https://github.com/shatakshigupta028/weatherly.git

# Go to the project directory
cd weatherly

# Open with VS Code
code .

# Right-click index.html → Open with Live Server
```

> Don't forget to install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VS Code if you haven't already.

---

## 🔑 API Setup

This project requires a free API key from OpenWeatherMap.

1. Create an account at [OpenWeatherMap](https://openweathermap.org/api).
2. Copy your API key.
3. In `assets/js/api.js`, replace:

```javascript
const api_key = "YOUR_API_KEY_HERE";
```
with your actual API key.

