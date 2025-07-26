# 🍎 Walmart Retail Sales Dashboard (2010–2012)

An Excel-based time series analysis and dashboard visualization project using real-world Walmart retail data. The dashboard includes KPIs, trend analysis, interactive charts, and seasonality insights.

---

## 📦 Repository Description

This repository contains a professional Excel dashboard project built as part of a data analytics learning journey. It showcases how to take raw Walmart retail data and turn it into a powerful analytical dashboard using only Microsoft Excel.

### 📂 Project Highlights:

- Cleaned and merged multi-sheet Kaggle dataset
- Monthly time series breakdown with KPIs
- Visual storytelling with slicers and chart interactivity
- Heatmaps, trends, seasonal insights, and more

---

## 📅 What This Dashboard Shows

- ✅ Monthly retail sales trend (2010–2012)
- ✅ Sales by store type (A/B/C)
- ✅ Top-performing department by weekly sales
- ✅ Promotion and holiday impact on revenue
- ✅ Key metrics like max sales, avg sales, lowest periods, and YoY change

---

## 🔎 What We Did

### 1. Data Sourcing

Used the [Walmart Sales Forecasting dataset](https://www.kaggle.com/competitions/walmart-recruiting-store-sales-forecasting):

- `train.csv`: Weekly sales by store & department
- `features.csv`: Temperature, fuel price, holidays, markdowns, etc.
- `stores.csv`: Store metadata (Type & Size)

### 2. Data Processing

- Merged all datasets using `Store` and `Date`
- Created `Key` column for lookups and data consistency
- Generated `Month` column to convert weekly to monthly format

### 3. KPI Calculation

Created a `KPI Summary` with:

- Peak Month
- Max Monthly Sales
- Avg Monthly Sales
- Top Store Type
- Top Dept by Weekly Sales
- Lowest Month & Sales Value

### 4. Dashboard Visuals

- 📈 Line Chart: Monthly Sales Trend
- 🍰 Pie Chart: Sales by Store Type
- 📊 Clustered Column: Sales by Month & Type
- 📉 Slicers: Month, Type (for interactivity)

### 5. Bonus

- Applied 3-month rolling average (trend smoothing)
- Used conditional formatting in table views
- Built with presentation formatting for exportability

---

## 📄 Files Included

```
walmart-retail-sales-dashboard/
├── dashboard/
│   └── Walmart_Retail_Sales_Dashboard.xlsx
├── images/
│   ├── dashboard_preview.png
│   └── demo.gif
├── insights/
│   └── insights_summary.md
└── README.md
```

---

## 💡 Key Insights

- 📅 **Top Month:** December 2010 ($288M+)
- 📊 **Store Type A** generated ~43% of total sales
- 🎉 **Holiday weeks** boosted avg sales by 60%
- 💼 **Promotional weeks** increased sales by ~21%
- 👩‍🌾 **Department 72** showed the highest weekly performance

---

## 💻 Tools Used

- Microsoft Excel:
  - Pivot Tables
  - Slicers & Dynamic Charts
  - Conditional Formatting
  - Line, Pie, and Clustered Column Charts

---

## 📸 Demo

![Dashboard Demo](images/demo.gif)

---

## 🙌 Author

Created as part of a practical time series breakdown exercise to demonstrate analytical thinking and Excel dashboarding.

Fork, star, or reuse this project for learning, interview prep, or to extend it using Power BI or Python!
