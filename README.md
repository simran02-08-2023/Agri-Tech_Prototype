📌 Overview

Agri-Tech is a smart farming advisory prototype designed to assist farmers with real-time monitoring, disease detection, advisory generation, and community interaction.
This project combines multiple features like sensor simulation, AI-powered chatbot, image-based disease diagnosis, and dashboards into one integrated platform.

⚠️ Note: This is a prototype for demonstration purposes only. It is not intended for production use.

🚀 Features
🔹 Sensor Dashboard

Simulated Soil Moisture, Temperature, Humidity, Battery, and Soil pH values

Real-time status indicator (Green / Amber / Red alerts)

Charts for soil moisture and temperature trends

Advisory generator with precision irrigation and soil health recommendations

🔹 Image Detection (Img)

Upload or capture crop leaf images

Mock AI classifier to detect Tomato, Potato, Wheat diseases

Displays disease name, confidence %, stage, severity

Provides treatment recommendations

🔹 Chat & Voice (AgriBot)

Farmers can ask queries related to irrigation, soil, pests, etc.

Gemini API placeholder integration (API key required at line ~813 in the code)

Voice/TTS support for advisory and active section content

Option to request agronomist visit (demo feature)

🔹 Knowledge Base

Searchable database of common crop diseases

Symptoms + treatment remedies in English & Hindi

🔹 Community Forum

Farmers can post and share tips/questions locally

🔹 Marketplace (Demo)

Mock product listings (e.g., organic compost, neem oil) with “Buy Now” buttons

🔹 Dashboard

Disease trend analysis chart

Outbreak heatmap (powered by Leaflet + OpenStreetMap)

Alerts section (monsoon, pest warnings)

🔹 Localization

Supports English and Hindi languages

🛠️ Tech Stack

Frontend: HTML, Tailwind CSS, JavaScript

Charts: Chart.js

Maps: Leaflet.js

Icons: FontAwesome

Voice: Web Speech API

⚙️ Setup & Usage

Clone or download this repository

git clone https://github.com/simran-02-08-2023/Agri-Tech-Prototype.git
cd Agri-Tech-Prototype


Open the project in VS Code

Run with Live Server extension

Right-click Agri-Tech_prototype.html → “Open with Live Server”

(Optional) Insert your Gemini API key at line 813 in the HTML file

const apiKey = "YOUR_API_KEY_HERE"; 
