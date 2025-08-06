# 🕵️ Credit Card Fraud Analysis

This repository contains a Python-based project for analyzing credit card transactions, identifying anomalies, and detecting potential fraudulent activities.

## 📌 Features
- Loads and processes transaction data
- Identifies important fraud indicators:
  - Transaction value spikes
  - IP address reuse
  - Shipping vs. billing mismatches
  - Suspicious high-volume purchases
- Detects common data issues
- Flags unusual transaction patterns
- Generates visualizations (e.g., total transaction value per user)

## 📊 Example Output
Example chart: **Total Transaction Value per User**

![Example Chart](assets/example_chart.png)

## 🗂 Project Structure

## ⚙️ Installation
1. Clone this repository:
```bash
git clone https://github.com/yourusername/fraud-analysis.git
cd fraud-analysis
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
python src/fraud_analysis.py
