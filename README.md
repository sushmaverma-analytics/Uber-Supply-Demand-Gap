# Uber Supply Demand Gap Analysis
Uber Supply Demand Gap Analysis using Python, EDA and Excel  Dashboard

### Uber Supply Demand Gap Analysis using Python, Exploratory Data Analysis (EDA) and Excel Dashboard

## 📌 Project Overview

This project analyzes Uber ride request data to identify supply-demand gaps, request patterns, peak hours, cancellations, and situations where cars were unavailable.

The analysis was performed using Python for Exploratory Data Analysis (EDA) and Microsoft Excel for interactive dashboard visualization.

The objective is to understand ride demand patterns and identify areas where driver availability can be improved to reduce cancellations and unfulfilled ride requests.

---

## 🎯 Business Problem

Uber needs to maintain a balance between customer ride demand and available drivers.

A mismatch between demand and driver availability can result in:

- Cancelled trips
- No cars available
- Lower customer satisfaction
- Lost business opportunities
- Inefficient driver allocation

This project analyzes the request data to identify these demand-supply gaps and provide actionable business recommendations.

---

## 🎯 Project Objectives

The main objectives of this project are:

1. Analyze Uber ride request patterns.
2. Understand trip status distribution.
3. Identify cancellation and unavailable-car patterns.
4. Analyze demand by pickup point.
5. Analyze request patterns by hour.
6. Identify potential supply-demand gaps.
7. Create an interactive Excel dashboard.
8. Provide business recommendations based on the analysis.

---

## 📊 Dataset

The dataset contains Uber ride request information including:

- Request ID
- Pickup Point
- Driver ID
- Status
- Request Timestamp
- Drop Timestamp

The dataset contains **6,745 ride requests**.

---

## 🛠️ Tools & Technologies

### Python
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Data Analysis
- Exploratory Data Analysis (EDA)
- Data cleaning
- Missing-value analysis
- Descriptive statistics
- GroupBy analysis
- Time-based analysis
- Data visualization

### Excel
- Pivot Tables
- Pivot Charts
- Dashboard
- Slicers
- KPI cards
- Interactive filtering

### GitHub
- Project documentation
- Version control
- Project portfolio

---

## 🔎 Exploratory Data Analysis

The following areas were analyzed using Python:

### 1. Dataset Structure

The dataset was examined using:

- `head()`
- `info()`
- `shape`
- `describe()`

### 2. Data Quality

The dataset was checked for:

- Missing values
- Data types
- Duplicate records
- Timestamp information
- Categorical values

### 3. Request Status Analysis

Ride requests were analyzed based on their status:

- Trip Completed
- No Cars Available
- Cancelled

### 4. Pickup Point Analysis

Requests were analyzed based on:

- Airport
- City

### 5. Hourly Demand Analysis

Request activity was analyzed across different hours of the day to identify periods of higher demand.

---

## 📈 Key Findings

The analysis contains **6,745 ride requests**.

The request-status distribution observed in the analysis is:

| Status | Requests |
|---|---:|
| Trip Completed | 2,831 |
| No Cars Available | 2,650 |
| Cancelled | 1,264 |
| **Total** | **6,745** |

### Important Observations

- Trip Completed represents the largest individual status category.
- A significant number of requests had **No Cars Available**, indicating a supply-side gap.
- A considerable number of requests were **Cancelled**.
- Demand patterns vary between Airport and City pickup points.
- Request volume changes throughout the day, indicating different demand periods.
- The analysis indicates that driver availability should be aligned with high-demand periods.

---

## 📊 Excel Dashboard

An interactive Excel dashboard was created to visualize the major findings.

### Dashboard Components

The dashboard includes:

- Total Request KPI
- Request Status analysis
- Request Hour analysis
- Pickup Point analysis
- Pickup Point vs Status analysis
- Interactive slicers

### Dashboard Filters

Users can filter the dashboard using:

- Pickup Point
- Status

The dashboard helps users quickly understand ride demand and supply-related problems.

---

## 💡 Business Insights

Based on the analysis:

### 1. Supply-Demand Gap

The high number of requests with no available cars indicates that driver supply does not always match customer demand.

### 2. Cancellations

Cancelled requests represent another important area for investigation because cancellations can negatively affect customer experience and business performance.

### 3. Peak Demand

Hourly analysis indicates that request volumes vary throughout the day. Driver availability should therefore be planned according to demand patterns.

### 4. Pickup Point Differences

Airport and City pickup points show different request patterns. Driver allocation can therefore be optimized separately for these locations.

---

## 🚀 Business Recommendations

Based on the findings, the following actions are recommended:

1. Increase driver availability during peak-demand periods.
2. Improve driver allocation between Airport and City locations.
3. Use historical request patterns to forecast future demand.
4. Monitor periods with high "No Cars Available" requests.
5. Analyze cancellation patterns to identify operational issues.
6. Continuously monitor supply-demand gaps using dashboards.
7. Optimize driver deployment based on time and pickup location.

---

## 📁 Project Files

| File | Description |
|---|---|
| `EDA.ipynb` | Complete Python Exploratory Data Analysis notebook |
| `EDA.pdf` | PDF version of the EDA analysis |
| `UBER FINAL Dashboard.pdf` | Final Excel dashboard |
| `Uber Request Data.xlsx` | Dataset and Excel analysis/dashboard |
| `README.md` | Project documentation |

---

## 🔄 Project Workflow

```text
Raw Uber Dataset
       ↓
Data Understanding
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Identify Supply-Demand Gaps
       ↓
Python Visualizations
       ↓
Excel Pivot Tables & Charts
       ↓
Interactive Dashboard
       ↓
Business Insights
       ↓
Recommendations



📌 Conclusion

The analysis demonstrates that Uber ride demand is not evenly distributed across time and pickup locations.

A significant number of ride requests were either cancelled or had no cars available, highlighting the importance of better driver allocation and demand forecasting.

Combining Python-based EDA with an Excel dashboard provides both analytical depth and an easy-to-understand business reporting solution.

👩‍💻 Author

Sushma Verma

Data Analytics Project

Skills demonstrated:

Python | Pandas | NumPy | EDA | Data Visualization | Excel | Pivot Tables | Pivot Charts | Dashboard | Business Insights


