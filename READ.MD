# E-Commerce Sales & Profit Analytics Dashboard

## Project Overview
This repository contains a comprehensive interactive sales and financial analysis dashboard designed to track sales volume, product demand, revenue performance, and regional profit margins across international markets.

---

## Key Metrics Summary
* **Total Stock Available:** 14K units
* **Sum of Quantity Purchased:** 152
* **Median Sales:** $6.38K
* **YTD Profit:** $933K
* **Net Revenue (USD):** $866.98K

---

## Dashboard Architecture & Features

### 1. Sales Overview
* **Median Sales Distribution by Country:** Analyzes sales distribution across primary markets, with the UAE holding the largest share ($68.08K / 63.49%), followed by France ($22.19K / 20.69%) and the UK ($14.4K / 13.43%).
* **Quantity Sold by Product:** Itemizes sales volume across individual SKUs to identify top-performing product categories.
* **Loyalty Points by Country:** Tracks customer engagement across global territories, led by the UK (315 points), USA (305 points), and Australia (262 points).
* **Median Sales Over Time:** Monitors performance trends and sales spikes from September 2023 through October 2023.

### 2. Profit Overview
* **Net Revenue by Product:** Ranks products by total net revenue generated, led by high-value inventory items such as the *Modular Sofa Set* ($93K), *Motion Sensor Alarm* ($72K), *Bamboo Plant Pot* ($71K), and *LED Garden Lights* ($68K).
* **Sum of Gross Revenue (USD) by Date:** Tracks revenue performance across the analysis period (2020 – 2023).
* **Yearly Profit Margin Analysis:** Displays overall margin stability across regions (~19.95% to 20.08% per country) with timeline tracking of profitability spikes over time.

---

## Interactive Filters & Controls
* **Date Range Slicer:** Filter all metrics across specified date ranges (default evaluation period: `1/1/2020` – `12/31/2023`).
* **Country Filter:** Multi-select functionality to isolate market performance (UAE, France, UK, Australia, USA).

---

## Data Structure
| Column Name | Description |
| :--- | :--- |
| `Date` | Transaction date |
| `Country` | Geographic market destination |
| `Product_Name` | Inventory item description |
| `Quantity_Purchased` | Units ordered per transaction |
| `Stock_Level` | Available inventory count |
| `Gross_Revenue_USD` | Total revenue prior to costs/discounts |
| `Net_Revenue_USD` | Final realized revenue |
| `Loyalty_Points` | Customer rewards accumulated |

---

