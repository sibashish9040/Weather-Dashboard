# Weather Monitoring Dashboard - Power BI

## 📍 Overview
This Power BI project presents a real-time weather dashboard with live data for Bhubaneswar and prominant cities of Odisha. The dashboard integrates dynamic visuals, rich weather insights, and a modern user interface.

The design focuses on ease of interpretation, color-coded metrics, and intuitive layout – built using Power BI for analytics and Figma for layout planning.

Data-source used here is [WeatherApi](https://www.weatherapi.com/)

---

## 🖼️ Dashboard Preview
![Dashboard Preview](https://github.com/sibashish9040/Weather-Dashboard/blob/main/Sample_picture.png)

---

## 🔧 Features

- 🌡️ **Current Weather Metrics**
  - Temperature, Humidity, Wind Speed
  - Visibility, Pressure, Precipitation
  - UV Index

- 📈 **7-Day Forecast Visualization**
  - Line chart displaying daily temperatures
  - Chronologically sorted day labels using DAX

- 🌅 **Sunrise & Sunset Times**
  - Real-time updates based on API data

- ☁️ **Chances of Rain**
  - Horizontal bar chart with percentage values for upcoming days

- 🌫️ **Air Quality Index (AQI)**
  - PM10, PM2.5, NO₂, SO₂, CO, and O₃ values
  - Circular gauge for PM10
  - Green/red indicators based on value thresholds

- 📍 **City Selector**
  - View current weather across cities like Bhubaneswar, Balasore, Cuttack, Koraput and Rourkela.

---

## ⚙️ Technical Stack

- **Data Source:** Weather API with live updates
- **Visualization Tool:** Power BI
- **Layout & UI Design:** Figma
- **Scripting:** DAX formulas for calculated measures, sorting, and conditional formatting

---

## 💡 Highlights

- Used `UNICHAR(8203)` and `REPT` in DAX to sort weekdays logically.
- Dynamic color formatting to indicate severity (e.g., AQI, precipitation).
- Figma-designed layout integrated seamlessly into Power BI visuals.
- Optimized for clarity, accessibility, and real-time insights.

---

## 🧪 Future Enhancements (Optional Ideas)

- Add hourly forecast view.
- Enable geolocation to auto-fetch weather for user’s location.
- Integrate historical weather trend comparison.

---
