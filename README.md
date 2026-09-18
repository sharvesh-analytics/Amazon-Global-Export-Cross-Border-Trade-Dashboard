# 🛒 Amazon Global Export & Cross-Border Trade Dashboard

[![Domain: E-Commerce](https://img.shields.io/badge/Domain-E--Commerce_%26_Trade-blue?style=for-the-badge&logo=amazon)](https://github.com/sharvesh-analytics)
[![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://github.com/sharvesh-analytics)
[![DAX Modeling](https://img.shields.io/badge/DAX-Analytics-orange?style=for-the-badge)](https://github.com/sharvesh-analytics)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

> **An executive cross-border trade analytics dashboard evaluating international shipping profitability, country-wise revenue growth, freight logistics costs, product category margins, and AI revenue forecasting for global sellers.**

---

## 📸Executive Visual Preview

<div align="center">
  <img src="Screenshot (22).png" width="48%" alt="Global Trade Overview Dashboard" />
  <img src="Screenshot (23).png" width="48%" alt="Cross-Border Freight & Country Analytics" />
</div>

<br />

<div align="center">
  <img src="Screenshot (24).png" width="80%" alt="Profitability & Category Margins" />
</div>

---

## 📌 Executive Summary

Expanding e-commerce sales across international borders requires real-time intelligence into cross-border logistics, tariff impacts, shipping overheads, and currency fluctuations. This dashboard provides **Amazon Global Trade operational managers** with:
- **Country Revenue & Profit Metrics**: Country-by-country breakdown of total export sales, gross profit, and unit volumes.
- **Logistics & Freight Efficiency Analysis**: Evaluation of shipping cost percentages vs. product revenue margins.
- **Product Category Analytics**: Identification of high-performing export categories (Electronics, Apparel, Home Goods).
- **Predictive AI Revenue Forecasting**: Forecasting next-quarter export demand and optimal inventory stock levels.

---

## 🛠️ Data Architecture & Pipeline

```mermaid
graph TD
    A[Amazon Global Export CSV Dataset] --> B[Data Cleaning & DAX Modeling]
    B --> C[Regional KPI Calculation Engine]
    C --> D[Logistics Cost & Margin Analysis]
    C --> E[AI Revenue Forecasting Engine]
    D --> F[Interactive Power BI Executive Dashboard]
    E --> F
```

---

## 📈 Key KPIs Tracked

- **Total Export Revenue**: Cumulative monetary value of cross-border orders.
- **Country Export Performance**: Top performing destination markets and sales volume growth.
- **Freight & Logistics Ratio**: Transport overhead vs. total margin percentage.
- **Product Category Profitability**: Net profit breakdown per product catalog segment.

---

## ⚡ Setup & Usage

### Prerequisites
- [Power BI Desktop](https://powerbi.microsoft.com/)

### Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/sharvesh-analytics/Amazon-Global-Export-Cross-Border-Trade-Dashboard.git
   ```
2. Open [`Amazon Global Export & Cross-Border Trade Dashboard.pbix`](<Amazon Global Export & Cross-Border Trade Dashboard.pbix>) in Power BI Desktop.
3. Dataset file [`Amazon_Global_Export_Cross_Border_Trade.csv`](Amazon_Global_Export_Cross_Border_Trade.csv) contains raw order records, shipping modes, country codes, and profit margins.

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for details.

---

<div align="center">
  <sub>Designed & Developed by <b>Sharvesh Pandey</b> | Data Analyst & BI Specialist</sub><br/>
  <a href="https://www.linkedin.com/in/sharvesh-analytics"><b>LinkedIn</b></a> • <a href="https://github.com/sharvesh-analytics"><b>GitHub Profile</b></a>
</div>
