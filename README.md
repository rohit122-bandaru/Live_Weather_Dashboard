
# 🌦️ Live Weather Power BI Dashboard

A real-time, auto-updating weather dashboard built with **Microsoft Power BI**, designed to display live and forecasted weather conditions, air quality levels, and more for selected cities in a beautiful and interactive format.

![Dashboard Preview](./Screenshot%202025-08-08%20005426.png)

---

## 📌 Features

- 🌡️ **Live Temperature & Weather Conditions**
  - Displays current temperature, mist/rain status, wind speed, humidity, visibility, and pressure.
- 📆 **7-Day Weather Forecast**
  - Interactive line chart with daily temperature trends.
- 🌅 **Sunrise and Sunset**
  - Shows today's sunrise and sunset times.
- 🌧️ **Chance of Rain**
  - Daily rain probability visualized with progress bars.
- 💨 **Air Quality Index**
  - Real-time AQI data (PM10, PM2.5, CO, NO2, SO2, O3) with color-coded severity.
- 🏙️ **Multi-City Comparison**
  - Switch between cities like Mumbai, Delhi, and Hyderabad.

---

## 🛠️ Tech Stack

- **Power BI Desktop**
- **Live Weather & AQI APIs** (e.g., OpenWeatherMap or similar)
- **DAX & Power Query**
- **Custom Cards, Charts, and Visual Elements**

---

## 🚀 How to Use

1. Clone or download the repository.
2. Open the `.pbix` file using [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Replace the API key(s) in the query editor (if needed).
4. Refresh the data to load live weather updates.
5. (Optional) Publish to Power BI Service for auto-refresh and cloud access.

---

## 🔄 Auto-Refresh

- The dashboard is configured to update periodically using API data.
- You can adjust refresh frequency in **Power BI Service** or use an **on-premises data gateway**.

---

## 🧩 Use Cases

- Daily personal or office weather monitoring
- Smart dashboard displays
- Data storytelling for weather and environment
- Educational or client-facing presentations

---

## 📁 Repository Contents

```bash
📦 Live-Weather-PowerBI-Dashboard
├── 📄 README.md
├── 🖼️ Screenshot 2025-08-08 005426.png
└── 📊 Live_Weather_Dashboard.pbix   # (Upload your PBIX file if applicable)
