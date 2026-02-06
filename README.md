# Secure Flight Log Analyzer

## Overview
A privacy-first flight log analysis prototype that anonymizes sensitive identifiers and detects anomalous engine behavior using explainable methods.

## Demo
- Google Colab (view-only): https://colab.research.google.com/drive/19z0Mz8ZWRl4THradNTVvMyupOWe7DEmT?usp=sharing
- GitHub Notebook Preview: Secure_Flight_Log_Analyzer.ipynb

## Features
- Anonymizes sensitive identifiers (pilot name → hashed ID)
- Rule-based and statistical anomaly detection
- Visualizes trends and flagged anomalies
- Simulates real-time monitoring via sequential processing

## Screenshots

### Anonymized Data
![Anonymized Data](screenshots/anonymized_data.png)

### Anomaly Detection
![Anomaly Detection](screenshots/anomaly_temperature.png)
![Anomaly Detection](screenshots/anomaly_vibration.png)

### Simulated Real-Time Alerts
![Alerts](screenshots/Alert_monitoring.png)

## Limitations
- Uses simulated data only
- Simulated real-time processing
- Educational prototype, not a production system
