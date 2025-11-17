# 🔐 Security Anomaly Detection Dashboard

This project is a React-based interactive dashboard designed to visualize, analyze, and detect anomalies in system logs. It supports log uploads, real-time streaming, severity-based analysis, KPI tracking, and CSV report generation. The system is built using **React + Vite** and provides an intuitive interface suitable for both students and cybersecurity practitioners.

We generated synthetic activity logs using two different AI models, QWEN and Google Gemini, and applied predefined rules to ensure that each log entry had a clear, intended classification. These synthetic datasets allowed us to test whether the dashboard correctly detected anomalies and assigned appropriate risk levels.

---

## 📌 Features

- Upload and parse log files (`.json`, `.txt`, `.csv`, `.log`)
- Automatic anomaly detection (critical, high, medium)
- Investigation Queue for suspicious events
- KPI and severity metrics
- Filtering by user, IP, and severity level
- Dark/Light mode toggle
- CSV report download
- Assets folder for sample datasets

---

## 🧰 Requirements

Before running the project, ensure you have:

- **Node.js v20 or higher**  
  Download: https://nodejs.org/

- **npm** (comes with Node)

Check your versions:

```bash
node -v
npm -v


