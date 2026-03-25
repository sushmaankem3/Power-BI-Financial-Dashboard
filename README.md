# Financial Performance Analysis Dashboard

Screenshots
Data Model

<img width="985" height="765" alt="image" src="https://github.com/user-attachments/assets/b7322365-91ff-4c32-8331-d7de68070148" />

Executive Overview

<img width="1371" height="772" alt="image" src="https://github.com/user-attachments/assets/5827ef90-36cd-4120-96e9-599fca7917b1" />

Customer Analysis

<img width="1382" height="771" alt="image" src="https://github.com/user-attachments/assets/4431eae6-798a-40a3-a5ea-df6958ae8244" />

## Overview
This project is a Power BI dashboard built to analyze financial performance across customers, time periods, and therapeutic areas. The report compares actual and forecast values, highlights revenue and margin trends, and supports interactive top/bottom customer analysis.

The dashboard is designed to answer questions such as:
- How are revenue, gross profit, and gross margin performing year over year?
- How do actuals compare against forecast?
- Which therapeutic areas contribute the most revenue?
- Which customer segments are high revenue but low margin?
- Who are the top and bottom customers by revenue or margin?

---

## Business Objectives
The report focuses on:
- Monitoring core financial KPIs
- Comparing actual vs forecast performance
- Identifying high-performing and low-performing customer segments
- Understanding revenue contribution by therapeutic area
- Supporting decision-making with dynamic filtering and ranking

---

## Data Model
The model follows a star-schema style structure.

### Tables
- **Fact Financials**
  - Revenue
  - Cost
  - RevenueUnitPrice
  - CostUnitPrice
  - RevenueVolume
  - CostVolume
  - Customer ID
  - Date
  - Year

- **Customer**
  - Customer ID
  - Customer Description
  - Therapeutic Area

- **Date**
  - Month
  - MonthName
  - MonthNumber
  - Quarter
  - QuarterSort
  - Year

- **Version**
  - Version
  - Year

## Key Metrics
The dashboard uses measures such as:
- **Total Revenue**
- **Total Cost**
- **Gross Profit**
- **Gross Margin %**
- **Revenue YoY Growth**
- **Gross Profit YoY Growth**
- **Gross Margin Variance vs LY**
- **Actual vs Forecast Revenue**
- **Top / Bottom Customer Ranking**

Report Pages
1. Executive Overview

Provides a summary of:

- Total Revenue
- Gross Profit
- Gross Margin %
- Revenue YoY Growth

Includes:

- KPI cards with year-over-year variance
- Revenue and gross profit trajectory
- Revenue by therapeutic area
- Revenue vs price/volume distribution
- High revenue / low margin segment analysis
  
2. Customer Performance Analysis

Focuses on:

- Gross Margin % by customer
- Top / Bottom customer analysis
- Revenue and cost by customer
- Quarter-based gross profit trends

Examples of insights supported by the dashboard:

- Revenue grew year over year, while gross margin slightly declined.
- Oncology contributes the largest share of revenue.
- Certain customer groups deliver strong revenue but below-average margin.
- Top customer performance can be dynamically compared against bottom customers using slicers.
- Forecast vs actual comparison highlights where financial expectations were exceeded or missed.

What I Learned

This project helped strengthen skills in:

Financial KPI design<br>
Actual vs forecast comparison<br>
DAX-based ranking and top/bottom analysis<br>
Dynamic slicer-driven reporting<br>
Dashboard layout and storytelling<br>
Building interactive reports with business-focused insights<br>





