# AQI_COLLECTOR

Author: Nanda Kumar

This project collects Air Quality Index (AQI) data from various cities and stores it for analysis.

## Features
- Collects AQI data from multiple Indian cities
- Stores air pollution components (CO, NO, NO2, O3, SO2, PM2.5, PM10, NH3)
- Includes weather data (temperature, humidity)
- Automated data collection via GitHub Actions

## Requirements
- OpenWeatherMap API key
- Python 3.x
- Required packages: requests, pandas, python-dotenv, logging

## Usage
1. Set your OpenWeatherMap API key as an environment variable or GitHub secret
2. Run `python collect_aqi.py` to collect data
3. Data will be stored in `data/AQI_dataset.csv`