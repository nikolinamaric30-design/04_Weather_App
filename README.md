# 🌤️ Weather Forecast

A comprehensive **Python Jupyter Notebook** for retrieving, visualizing, and exporting weather forecasts.  
This notebook fetches real-time weather data from **Open-Meteo** and provides interactive charts, tables, and maps for a selected city.

---

## 🌟 Features

### **1. Weather Forecast Data**
- Retrieves **hourly weather forecasts** (temperature, humidity, wind speed, precipitation, and more).
- Supports a **3-day forecast**.
- Converts weather codes into **emoji-based icons** for easier interpretation.

---

### **2. Interactive Dashboard**
- **Dynamic tables** for each day, highlighting upcoming hours.
- **Static graphs** for temperature, humidity, feels like, and more.
- **Animated Plotly graph** showing trends over time.
- **Interactive city map** (OpenStreetMap).
- **Daily weather tips** based on forecast conditions.

---

## 📤 Data Export

The application provides several export options to help you store, analyze, and share forecast data and visualizations.

### 📁 **Available Export Formats**
- **CSV — `forecast_3d.csv`**  
  Raw forecast data suitable for further analysis.
- **Excel — `forecast_3d.xlsx`**  
  A clean, structured spreadsheet version of the 3-day forecast.
- **Static HTML — `forecast_3days_static.html`**  
  A static Plotly 3-day weather visualization.
- **Interactive HTML — `forecast_3d.html`**  
  An offline interactive Plotly graph for detailed inspection.
- **Map HTML — `weather_map.html`**  
  An exported interactive weather map.

### ✅ **Export Confirmation**
After export, the application prints a confirmation message listing all saved files.

---

## ▶️ Usage

1. Enter a city name in the input field.
2. Run all notebook cells to fetch data.
3. Explore:
   - Daily forecast tables  
   - Interactive & static charts  
   - City map with weather context  
4. Export your data and graphs via the **Export Section**.
5. Files will be saved to: exported_forecast/



## 🖼️ Screenshots

### 📅 Daily Forecast Table
A styled and color-coded table showing the hourly forecast for the selected day.  
Highlights future hours and includes emoji weather icons for easier interpretation.

<img width="811" height="600" alt="image" src="https://github.com/user-attachments/assets/09354822-75f2-4113-b108-2d6a7d35a8c5" />


### 📊 Static Weather Graph
A clean, static Plotly chart visualizing temperature, humidity, and other key metrics.  
Ideal for exporting into reports or viewing without interactivity.

<img width="1901" height="873" alt="image" src="https://github.com/user-attachments/assets/576f180a-9181-47b8-bba9-bbcfb49a82e5" />


### 📈 Interactive Forecast Graph
An interactive Plotly chart that allows zooming, panning, toggling parameters, and viewing detailed trends across the forecast.

<img width="1883" height="877" alt="image" src="https://github.com/user-attachments/assets/69e99f5b-2f14-4d82-8ae5-3cf9607a283a" />


### 🗺️ City Weather Map
A fully interactive map showing the exact geographic location of the selected city,  
including weather-based markers and additional contextual information.

<img width="885" height="569" alt="image" src="https://github.com/user-attachments/assets/dc4909e6-a323-49f7-9047-71d6a6c5e4f6" />


### Notes
- Uses Open-Meteo API for weather forecasts (free & no API key required).
- Geocoding is done via geopy and OpenStreetMap.
- Tables are styled and color-coded for easy reading.
- Interactive graphs are fully exportable as HTML.

### Contact

- Developed by Nikolina Maric – nikolina.maric.30@gmail.com
- GitHub: https://github.com/nikolinamaric30-design
