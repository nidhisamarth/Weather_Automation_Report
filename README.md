# Weather_Automation_Report
This project is an n8n workflow that automates fetching and delivering daily weather reports using an external weather API. It’s designed to simplify weather updates for individuals or teams by scheduling reports and sending them automatically to preferred channels.


Weather Report Automation (n8n)

This project is an n8n workflow that automates fetching and delivering daily weather reports using an external weather API. It’s designed to simplify weather updates for individuals or teams by scheduling reports and sending them automatically to preferred channels.

✨ Features

Fetches live weather data (temperature, humidity, wind, conditions)

Scheduled execution using Cron

Formats weather into a clear, readable report

Sends updates via Email, Slack, or Telegram (customizable)

Easy to adapt for multiple cities or data sources

🔧 Tech Stack

n8n.io (workflow automation)

Weather API (e.g., OpenWeatherMap or similar)

Email / Slack integrations

JSON data processing

🚀 Workflow Steps

Trigger – Starts on a schedule (e.g., every morning)

HTTP Request – Calls the weather API for live data

Function Node – Formats the raw JSON response

Notification Node – Sends the weather summary report

📂 Repository

weather-report.json → Exported workflow file (importable into n8n)

README.md → Documentation for setup and usage

🛠️ Setup

Clone this repo

Import weather-report.json into your n8n instance

Add your API key for the weather service

Configure Email/Slack credentials in n8n

Activate the workflow 🎉

🔮 Future Enhancements

Severe weather alerts

Multi-city reports with side-by-side data

Store history in Google Sheets or a database
