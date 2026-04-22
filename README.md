# 🛒 Superstore Sales Analysis — Excel Project with Dashboard
This repository consists of uncleaned input data file, cleaned data file including dashboard and dashboard image.
An end-to-end sales analytics project built in Microsoft Excel, exploring 4 years of U.S. Superstore transactional data (2015–2018) across product categories, customer segments, regions, and shipping modes — all visualized in an interactive dashboard.

---

## 📊 Project Overview

This project analyzes **9,800 sales transactions** from a fictional U.S. Superstore to uncover trends, top-performing segments, and operational insights. The entire workflow — from raw data to KPI calculation to visualization — is contained within a single Excel workbook.

| Metric | Value |
|---|---|
| Total Sales | $2,261,536.78 |
| Total Orders | 9,800 |
| Average Sales per Order | $230.77 |
| Maximum Single Sale | $22,638.48 |
| Top Category | Technology |
| Top Region | South |

---
## Repository Structure

```
superstore-sales-analysis/ 
│
├── 📄 README.md
├── 📊 Tarmin's Excel Project.xlsx
├── 📋 Input file_ Superstore sales.csv
└── 📑 dashboard.pdf
```

## 📁 File Structure

```
Tarmin_s_Excel_Project.xlsx
│
├── Input file_ Superstore sales   # Clean dataset (9,800 rows × 19 columns)
├── KPI                            # Summary KPI cards
├── Bar Chart                      # Order count by shipping mode
├── XLOOKUP                        # Product lookup sheet (XLOOKUP formula demo)
├── Sales Trend                    # Monthly sales trend (PivotTable)
├── Sales by region                # Sales breakdown by U.S. state
├── Category Sales                 # Sales by product category
├── Sub-Category Sales             # Sales by product sub-category
├── Segment Sales                  # Sales by customer segment
├── Shipping Mode Analysis         # Sales by shipping method
└── DASHBOARD                      # Interactive sales dashboard
```

---

## 🗂️ Dataset Description

**Sheet:** `Input file_ Superstore sales`

The raw dataset contains the following 19 fields:

| Column | Description |
|---|---|
| Row ID | Unique row identifier |
| Order ID | Unique order identifier |
| Order Date | Date the order was placed |
| Ship Date | Date the order was shipped |
| Ship Mode | Shipping method used |
| Customer ID | Unique customer identifier |
| Customer Name | Name of the customer |
| Segment | Customer segment (Consumer, Corporate, Home Office) |
| Country | Country of the order |
| City | City of the order |
| State | U.S. state of the order |
| Postal Code | Postal code |
| Region | U.S. region (Central, East, South, West) |
| Product ID | Unique product identifier |
| Category | Product category |
| Sub-Category | Product sub-category |
| Product Name | Full name of the product |
| Sales | Revenue from the order line ($) |
| Order Date (YYYY/MM) | Derived month-year field for trend analysis |

**Date range:** January 2015 – December 2018  
**Geography:** United States (50 states + D.C.)

---

## 🔍 Analysis Sheets

### KPI Summary
High-level performance indicators calculated directly from the raw data:
- Total Sales, Total Orders, Average Sales per Order, Max Sales, Top Category, Top Region

### Sales Trend
Monthly sales aggregated using a PivotTable to track revenue growth over time from 2015 to 2018.

### Sales by Region
State-level sales breakdown across all 50 U.S. states. Top states include:
- **California** — $446,306.46
- **New York** — $306,361.15
- **Texas** — $168,572.53

### Category Sales
| Category | Sales |
|---|---|
| Technology | $827,455.87 |
| Furniture | $728,658.58 |
| Office Supplies | $705,422.33 |

### Sub-Category Sales
17 sub-categories analyzed — top performers include **Phones** ($327,782), **Chairs** ($322,823), and **Storage** ($219,343).

### Segment Sales
| Segment | Sales |
|---|---|
| Consumer | $1,148,060.53 |
| Corporate | $688,494.07 |
| Home Office | $424,982.18 |

### Shipping Mode Analysis
| Ship Mode | Sales |
|---|---|
| Standard Class | $1,340,831.31 |
| Second Class | $449,914.18 |
| First Class | $345,572.26 |
| Same Day | $125,219.04 |

### XLOOKUP Sheet
Demonstrates the use of Excel's **XLOOKUP** function to retrieve product details (Name, Category, Sub-Category) by Product ID — a practical example of dynamic lookups in large datasets.

---

## 🛠️ Excel Features & Techniques Used

- **PivotTables** — used for all aggregation across regions, categories, segments, and shipping modes
- **XLOOKUP** — dynamic product lookup by ID
- **KPI Cards** — summary metrics for quick performance review
- **Charts & Visualizations** — bar charts for shipping mode distribution and other visuals
- **Slicers** — interactive filters on the dashboard for drill-down analysis
- **Date Engineering** — derived `Order Date (YYYY/MM)` column for time-series analysis
- **Dashboard Design** — consolidated view combining KPIs and charts in one sheet

---

## 💡 Key Insights

1. **Technology is the top revenue category**, contributing ~37% of total sales.
2. **Consumer segment drives the majority of revenue** (~51%), nearly doubling Corporate.
3. **Standard Class shipping dominates** (~59% of sales), suggesting customers prioritize cost over speed.
4. **California and New York are the top two states**, together accounting for ~33% of total sales.
5. **The South region leads** across all four U.S. regions.

---

## 🚀 How to Use

1. **Download** the `Tarmin_s_Excel_Project.xlsx` file.
2. **Open** in Microsoft Excel (2019 or later recommended for XLOOKUP support).
3. Navigate to the **DASHBOARD** sheet for an interactive overview.
4. Use the **Slicers** on the dashboard to filter by region, category, or segment.
5. Explore individual analysis sheets for deeper breakdowns.

> **Note:** Some features (Slicers, XLOOKUP) require Excel 2019+ or Microsoft 365. The file may have limited functionality in older versions or Google Sheets.

---

## 📌 Requirements

- Microsoft Excel 2019 / Microsoft 365 (recommended)
- No external add-ins or macros required

---

## 👤 Author

**Tarmin**  
Data Analyst  

---


