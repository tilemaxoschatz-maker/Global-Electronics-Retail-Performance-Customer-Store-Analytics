# Global Electronics Retail Performance, Customer & Store Analytics

**End-to-end retail analytics portfolio project built natively in Google Sheets**

This project transforms **62,884 sales lines** from a multi-table global electronics retail dataset into management-ready insights about **revenue, profitability, product performance, brands, customers, geography, sales channels, store performance, seasonality, and online delivery efficiency**.

> **Best viewing experience:** open the native Google Sheets version below. The `.xlsx` file can also be included as a downloadable copy, but some chart positions, formatting, merged cells, and Google Sheets-specific features may look different after Excel export.

## Live Project

**[▶ View the full native Google Sheets workbook](https://docs.google.com/spreadsheets/d/16IoxGfunyiEUEiMkG1U0f4kbpdwyH9XTm5sAwY8qPJQ/edit)**

### Downloads

- **[Download the Excel export](./Global%20Electronics%20Retail%20Performance%2C%20Customer%20%26%20Store%20Analytics.xlsx)**

---

## Dashboard Preview

<p align="center">
  <img src="dashboard_preview/dashboard-overview.png" alt="Global Electronics Retail Performance Dashboard" width="100%">
</p>

<p align="center">
  <img src="dashboard_preview/dashboard-detail.png" alt="Global Electronics Retail Dashboard Detail" width="100%">
</p>

---

## Project Overview

| Item | Description |
|---|---|
| **Business objective** | Evaluate retail performance, profitability, customer markets, store activity, channel mix, and operational efficiency |
| **Dataset** | Multi-table global electronics retail dataset |
| **Analysis period** | January 2016 – February 2021 |
| **Data volume** | 62,884 sales lines across 26,326 orders |
| **Primary tool** | Google Sheets |
| **Supporting techniques** | Data cleaning, formulas, lookup-based modeling, pivot tables, charts, KPI reporting |
| **Primary metrics** | Revenue, cost, profit, margin, orders, units sold, customers, products, average order value |

---

## Business Objective

The analysis goes beyond basic sales reporting to answer a broader management question:

> **What is driving retail revenue and profit, where is performance concentrated, how are channels and locations performing, and what actions could strengthen growth and operational efficiency?**

The project evaluates not only total revenue, but also the **quality and concentration of performance** across products, brands, customer markets, physical locations, channels, and time.

---

## Business Questions

1. How have revenue and profit developed over time?
2. Which product categories and brands generate the strongest performance?
3. Which customer countries contribute the most revenue and profit?
4. How important are physical stores compared with the online channel?
5. Which physical store states generate the strongest revenue?
6. How has online delivery performance changed over time?
7. What seasonal patterns appear in monthly sales?
8. Where are the main areas of concentration and business risk?

---

## Analytical Workflow

```text
RAW DATA
   ↓
DATA AUDIT
   ↓
CLEAN DATA
   ↓
MODELED SALES TABLE
   ↓
ANALYSIS SUMMARY
   ↓
PIVOT ANALYSIS
   ↓
CHART LIBRARY
   ↓
DASHBOARD
   ↓
EXECUTIVE INSIGHTS
```

The workbook follows a structured end-to-end analytics process:

1. **Raw data preservation** — keeps the original source tables intact for traceability.
2. **Data audit** — checks row counts, duplicate keys, missing values, and data consistency.
3. **Data cleaning** — creates clean versions of sales, customer, product, store, and exchange-rate tables.
4. **Data modeling** — combines the source tables into a 42-column analytical sales model.
5. **Feature engineering** — adds channel, delivery, customer age, revenue, cost, profit, margin, time, and local-currency fields.
6. **Analysis summary** — calculates high-level business KPIs with spreadsheet formulas.
7. **Pivot analysis** — analyzes time, products, brands, channels, stores, customer geography, and delivery performance.
8. **Chart library** — provides a broader visual analysis layer beyond the executive dashboard.
9. **Dashboard development** — presents the strongest KPIs and trends in a management-ready visual layout.
10. **Executive insights** — converts the analysis into conclusions and business recommendations.

---

## Workbook Structure

| Worksheet | Purpose |
|---|---|
| `RAW_SALES` | Original sales transactions |
| `RAW_CUSTOMERS` | Original customer master data |
| `RAW_PRODUCTS` | Original product master data |
| `RAW_STORES` | Original store master data |
| `RAW_EXCHANGE_RATES` | Original daily exchange-rate data |
| `DATA_DICTIONARY` | Field definitions and dataset documentation |
| `DATA_AUDIT` | Data-quality and validation checks |
| `CLEAN_SALES` | Cleaned sales data |
| `CLEAN_CUSTOMERS` | Cleaned customer data |
| `CLEAN_PRODUCTS` | Cleaned product data |
| `CLEAN_STORES` | Cleaned store data |
| `CLEAN_EXCHANGE_RATES` | Cleaned exchange-rate data |
| `MODEL_SALES` | Central 42-column analytical fact table |
| `ANALYSIS_SUMMARY` | Formula-driven KPI summary and annual performance |
| `PIVOT_ANALYSIS` | Detailed business analysis across seven pivot views |
| `CHARTS` | Visual analysis library with ten charts |
| `DASHBOARD` | Executive KPI and performance dashboard |
| `EXECUTIVE_INSIGHTS` | Executive conclusions and strategic recommendations |

---

## Engineered Features

The modeled sales table extends the raw source data with analytical variables including:

- Sales line key
- Sales channel
- Delivery days
- Customer geography
- Customer age at order
- Product brand
- Product subcategory
- Product category
- Store geography
- Store size
- Exchange rate
- Revenue USD
- Cost USD
- Profit USD
- Profit margin
- Revenue in local currency
- Order year
- Order month
- Order month number
- Order quarter
- Order year-month

These variables make it possible to analyze not only sales volume, but also **profitability, customer concentration, channel performance, physical-store performance, and operational efficiency**.

---

## Executive Performance Snapshot

| KPI | Result |
|---|---:|
| **Total Revenue** | **$55.76M** |
| **Total Cost** | **$23.09M** |
| **Total Profit** | **$32.66M** |
| **Overall Profit Margin** | **58.58%** |
| **Total Orders** | **26,326** |
| **Total Sales Lines** | **62,884** |
| **Units Sold** | **197,757** |
| **Unique Customers** | **11,887** |
| **Unique Products Sold** | **2,492** |
| **Average Order Value** | **$2,117.89** |

> **2021 is a partial year and includes data through February only.**

---

# Key Business Insights

## 1. Revenue expanded strongly through 2019 before a major decline

Revenue increased from approximately **$6.95M in 2016** to a peak of approximately **$18.26M in 2019**.

Revenue then fell to approximately **$9.29M in 2020**. The 2021 figure should not be compared directly with prior full years because the dataset ends in February 2021.

**Business implication:** the post-2019 decline is one of the most important performance patterns requiring deeper investigation.

---

## 2. Computers are the strongest product category

Computers generated approximately **$19.30M in revenue** and more than **$11.27M in profit**, making the category the leading contributor by both measures.

**Business implication:** Computers represent a core commercial strength and should remain a priority for availability, pricing, promotion, and cross-selling.

---

## 3. Customer revenue is highly concentrated in the United States

The United States generated approximately **$29.87M in revenue**, representing roughly **54% of total company revenue**.

The United Kingdom, Germany, and Canada are the next-largest customer markets.

**Business implication:** the company benefits from a strong U.S. position but also carries geographic concentration risk.

---

## 4. Physical stores dominate the current channel mix

Physical stores generated approximately **$44.35M**, compared with approximately **$11.40M from online sales**.

This means physical stores contribute about **80% of total revenue**, while online contributes about **20%**.

**Business implication:** physical retail remains the primary revenue engine, but the online channel provides an important diversification and growth opportunity.

---

## 5. Online delivery efficiency improved materially

Average online delivery time declined from approximately **7.3 days in 2016** to approximately **3.8 days in 2021**.

**Business implication:** the business has made measurable operational improvements in online fulfillment, creating a stronger foundation for digital growth.

---

## 6. Store performance is distributed across several strong physical markets

Among physical store states, **Nevada, Kansas, and Nebraska** rank among the strongest by revenue.

**Business implication:** management should identify the practices or market characteristics supporting these locations and test whether they can be replicated elsewhere.

---

## 7. Monthly performance shows clear seasonality

The monthly trend shows recurring peaks and troughs, including particularly strong year-end sales.

**Business implication:** inventory, staffing, marketing, and promotional planning should reflect recurring seasonal demand patterns.

---

## 8. Brand performance is concentrated among a small group of leaders

**Adventure Works, Contoso, Wide World Importers, and Fabrikam** are among the strongest brands by revenue and profit.

**Business implication:** brand-level planning should protect high-value brands while identifying opportunities to improve lower-performing parts of the portfolio.

---

# Strategic Recommendations

### 1. Protect and expand the Computers business

Prioritize product availability, pricing discipline, promotions, high-performing brands, and cross-selling around the strongest category.

### 2. Reduce geographic concentration

Use the United Kingdom, Germany, Canada, and other established markets as logical targets for focused customer acquisition and growth initiatives.

### 3. Continue developing the online channel

Build on the major improvement in delivery performance to support digital customer growth and reduce dependence on physical stores.

### 4. Investigate the post-2019 decline

Analyze customer demand, product mix, store performance, geography, and channel activity to identify which factors contributed most to the decline.

### 5. Use seasonality in commercial planning

Align inventory, staffing, campaigns, and promotional activity with recurring monthly demand patterns.

### 6. Benchmark high-performing physical locations

Study leading states such as Nevada, Kansas, and Nebraska and evaluate which practices can be transferred to weaker physical-store markets.

---

## Selected Analysis Charts

### Top 10 Physical Store States by Revenue

<p align="center">
  <img src="analysis_charts/top-10-physical-store-states-by-revenue.png" alt="Top 10 Physical Store States by Revenue" width="90%">
</p>

### Profit by Product Category

<p align="center">
  <img src="analysis_charts/profit-by-product-category.png" alt="Profit by Product Category" width="90%">
</p>

### Profit by Brand

<p align="center">
  <img src="analysis_charts/profit-by-brand.png" alt="Profit by Brand" width="90%">
</p>

---

## Chart Library

The `CHARTS` worksheet contains ten supporting visuals:

1. **Yearly Revenue & Profit Performance**
2. **Monthly Revenue & Profit Trend**
3. **Revenue by Product Category**
4. **Revenue by Brand**
5. **Revenue by Customer Country**
6. **Revenue by Sales Channel**
7. **Average Online Delivery Days by Year**
8. **Top 10 Physical Store States by Revenue**
9. **Profit by Product Category**
10. **Profit by Brand**

The executive dashboard intentionally uses only the strongest six visuals so the management view remains focused and uncluttered.

---

## Dashboard Design

The executive dashboard follows a management-focused structure:

```text
EXECUTIVE HEADER
      ↓
KPI CARDS
      ↓
ANNUAL & MONTHLY TRENDS
      ↓
PRODUCT & CUSTOMER GEOGRAPHY
      ↓
CHANNEL & OPERATIONAL PERFORMANCE
      ↓
KEY BUSINESS INSIGHTS
```

The dashboard includes five headline KPIs:

- Total Revenue
- Total Profit
- Profit Margin
- Total Orders
- Average Order Value

The six dashboard visuals are:

- Yearly Revenue & Profit Performance
- Monthly Revenue & Profit Trend
- Revenue by Product Category
- Revenue by Customer Country
- Revenue by Sales Channel
- Average Online Delivery Days by Year

---

## Repository Structure

```text
global-electronics-retail-analytics/
├── README.md
├── Global Electronics Retail Performance, Customer & Store Analytics.xlsx
│
├── dashboard_preview/
│   ├── dashboard-overview.png
│   └── dashboard-detail.png
│
└── analysis_charts/
    ├── top-10-physical-store-states-by-revenue.png
    ├── profit-by-product-category.png
    └── profit-by-brand.png
```

---

## How to Use the Project

1. **Open the native Google Sheets workbook first** for the intended layout and formatting.
2. Review the dashboard screenshots above for a quick management-level overview.
3. Use `DATA_DICTIONARY` to understand the dataset fields.
4. Use `DATA_AUDIT` to review the data-quality checks.
5. Review the cleaned source tables for the preparation process.
6. Review `MODEL_SALES` to understand the analytical data model and engineered fields.
7. Review `ANALYSIS_SUMMARY` for the high-level KPI calculations.
8. Review `PIVOT_ANALYSIS` for detailed business breakdowns.
9. Review `CHARTS` for the complete supporting visual analysis.
10. Review `DASHBOARD` for the executive management view.
11. Review `EXECUTIVE_INSIGHTS` for final conclusions and strategic recommendations.
12. Use the `.xlsx` export only when a local Excel copy is required; visual formatting may differ from the native Google Sheets version.

---

## Skills Demonstrated

### Data Preparation

- Multi-table data cleaning
- Data validation and audit checks
- Duplicate-key validation
- Missing-value assessment
- Source-data preservation
- Structured analytical workflow

### Data Modeling

- Multi-table integration
- Customer enrichment
- Product enrichment
- Store enrichment
- Exchange-rate integration
- Central analytical fact-table design
- Lookup-based spreadsheet modeling

### Feature Engineering

- Date-based features
- Channel classification
- Delivery-performance metrics
- Customer age calculation
- Revenue calculation
- Cost calculation
- Profit calculation
- Profit margin
- Currency conversion
- Year, month, quarter, and year-month dimensions

### Spreadsheet Analytics

- Google Sheets
- Microsoft Excel interoperability
- Spreadsheet formulas
- Dynamic references
- `SUMIFS`
- `FILTER`
- `UNIQUE`
- `COUNTUNIQUE`
- `IF`
- `IFERROR`
- `DATEDIF`
- Date functions
- Calculated business metrics

### Pivot Analysis

- Time-series aggregation
- Product category analysis
- Brand analysis
- Customer geography analysis
- Channel analysis
- Store performance analysis
- Operational delivery analysis

### Data Visualization

- Executive dashboard design
- KPI cards
- Revenue and profit trend charts
- Horizontal ranking charts
- Product performance charts
- Brand performance charts
- Geographic comparisons
- Channel comparisons
- Operational performance visualization

### Business Analytics

- Revenue analysis
- Cost analysis
- Profitability analysis
- Product performance
- Brand performance
- Customer geography
- Store performance
- Channel mix
- Seasonality
- Online fulfillment performance

### Business Communication

- Translating analytical findings into business insights
- Executive reporting
- Strategic recommendations
- Management-focused storytelling
- Portfolio case-study development

---

## Tools

- **Google Sheets**
- **Microsoft Excel**
- Spreadsheet formulas
- Pivot Tables
- Feature Engineering
- Data Modeling
- Data Visualization
- Business Analytics

---

## Data Source

This portfolio project uses a **multi-table global electronics retail dataset** containing sales transactions together with customer, product, store, and exchange-rate reference data.

The source structure includes:

- Sales transactions
- Customer master data
- Product master data
- Store information
- Historical exchange rates

---

## Disclaimer

This project is intended for **portfolio and educational purposes**. The dataset is used to demonstrate an end-to-end retail analytics workflow and should not be interpreted as the financial performance of a real company.
