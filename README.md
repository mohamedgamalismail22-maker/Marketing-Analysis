# Marketing-Analysis
Marketing Analysis
# 🧩 FixIt Pro – Seasonal Service Performance Dashboard

## 📊 Overview
This Power BI project analyzes data from **FixIt Pro**, a home services company that offers **seasonal service bundles** such as HVAC and Plumbing.  
The goal is to understand **which service types foster customer loyalty**, identify **high-performing ad channels**, and track **spending efficiency** across different time periods.

---

## 🎯 Objectives
- Measure **ROI (Return on Investment)** across all ad channels.  
- Analyze **conversion rates** and **returning customer percentages**.  
- Compare performance between **Bundled, Premium, and Basic services**.  
- Detect **seasonal or time-based booking trends** to optimize marketing efforts.  

---

## 📈 Dashboard Pages

### 🟩 1. Spend & Revenues
- Displays **Total Revenue, Ad Spend, and ROI**.  
- Compares **Revenue and Spend by Ad Channel and Customer Type**.  
- Includes **trend analysis over time** for ad efficiency.  
- ROI formula used:  
- **Key Insight:** Facebook and In-Store channels show the highest ROI, making them the most cost-efficient platforms.

---

### 🟦 2. Conversions & Returning
- Shows **Total Conversions, Conversion Rate, and Returning Rate**.  
- Breaks down conversions by **Service Type, Ad Channel, and Time of Day**.  
- Helps identify which services generate **repeat bookings** and **customer loyalty**.  
- **Key Insight:** Bundled services achieve the highest returning rate, indicating stronger customer satisfaction and retention.

---

## 🧠 Key Metrics (DAX Measures)
```DAX
-- ROI
ROI = DIVIDE([Total Revenue] - [Ad Spend], [Ad Spend])

-- Conversion Rate
Conversion Rate = DIVIDE([Conversions], [Ad Spend])

-- Returning Rate
Returning Rate = DIVIDE([Returning Customers], [Total Customers])
