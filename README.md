# 📊 Task 4 — Sales & Financial Dashboard Design

**Data Analyst Internship | Elevate Labs × Ministry of MSME, Govt. of India**

---

## 🎯 Objective

Design an interactive dashboard for business stakeholders that communicates sales trends, product performance, regional breakdown, and key financial KPIs — enabling data-driven decisions from a single view.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Google Looker Studio | Dashboard creation & interactivity |
| Kaggle | Dataset source |
| Google Sheets | Data cleaning & import |
| PowerPoint (pptxgenjs) | Summary presentation |

---

## 📁 Repository Structure


Interactive-Dashboard
│
├── README.md                        # This file
├── Task4_Dashboard_PPT.pptx         # Summary presentation (7 slides)



---

## 📦 Dataset

**Source:** [Kaggle — Sales Data Sample](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)

| Field | Description |
|-------|-------------|
| `ORDERNUMBER` | Unique order identifier |
| `ORDERDATE` | Date of order |
| `SALES` | Revenue per order line ($) |
| `QUANTITYORDERED` | Units ordered |
| `PRICEEACH` | Unit price |
| `PRODUCTLINE` | Category (Classic Cars, Vintage Cars, etc.) |
| `DEALSIZE` | Small / Medium / Large |
| `STATUS` | Shipped, Cancelled, On Hold, etc. |
| `TERRITORY` | North America, EMEA, Asia Pacific, Japan |
| `COUNTRY` | 19 countries |

**Total records:** 2,823 orders across 2003–2005

---

## 📈 Dashboard Features

### KPI Scorecards
- **Total Revenue** — $10.0M
- **Total Orders** — 2,823
- **Average Order Value** — $35.4K
- **Fulfillment Rate** — 92.5%

### Charts & Visuals
| Chart | Type | Insight |
|-------|------|---------|
| Monthly Revenue Trend | Time-series line | Q4 (Nov) is peak month |
| Sales by Product Line | Horizontal bar | Classic Cars = 39% of revenue |
| Sales by Territory | Column bar | EMEA leads at $4.69M |
| Revenue by Deal Size | Pie/Donut | Medium deals dominate at 61% |
| Order Status | Donut | 92.5% shipped, 2.1% cancelled |

### Interactive Controls (Slicers)
- **Year** — Filter by 2003, 2004, 2005
- **Product Line** — Classic Cars, Vintage Cars, Motorcycles, etc.
- **Territory** — North America, EMEA, Asia Pacific, Japan
- **Deal Size** — Small, Medium, Large

All slicers update every chart on the page simultaneously.

---

## 💡 Key Business Insights

1. **Classic Cars** is the dominant product line at **$3.9M (39%)** of total revenue — prioritize inventory and marketing here.
2. **EMEA** leads all territories with **$4.69M** in sales — strong European market presence.
3. **November** is consistently the highest-revenue month — align promotions and stock ahead of Q4.
4. **92.5% fulfillment rate** shows strong operations, but **104 at-risk orders** (cancelled + on hold) warrant investigation.
5. **Medium deal sizes** account for 61% of revenue — sales strategy should target mid-tier customers.

---

## 🎨 Dashboard Design Principles Applied

- ✅ Consistent navy + coral color theme throughout
- ✅ KPI cards at top for immediate executive summary
- ✅ Slicers/filters for full interactivity
- ✅ Time-series analysis for trend visibility
- ✅ Navigation-friendly layout with logical flow
- ✅ Mix of chart types (line, bar, donut, pie) for variety

---

## 🔗 Live Dashboard

> [Click here to view the interactive Looker Studio dashboard](#)  
> *(Replace `#` with your published Looker Studio link)*

---

## 📽️ Deliverables

| Deliverable | Status |
|-------------|--------|
| Interactive Dashboard (Looker Studio) | ✅ Complete |
| PPT Summary (7 slides) | ✅ Complete |
| README / GitHub documentation | ✅ Complete |

---

## 🚀 How to Reproduce

1. Download `sales_data_sample.csv` from the `data/` folder (or directly from Kaggle)
2. Import into **Google Looker Studio** via Google Sheets connector
3. Create the following charts using the field mappings above
4. Add drop-down controls for Year, Product Line, Territory, Deal Size
5. Apply a consistent theme (navy `#1E2761` + accent `#F96167`)

---

## 👤 Author

**Sabarish P**  
Elevate Labs — Ministry of MSME, Govt. of India  
Task 4: Dashboard Design

---

*Built with Google Looker Studio | Dataset: Kaggle Sales Data Sample*
