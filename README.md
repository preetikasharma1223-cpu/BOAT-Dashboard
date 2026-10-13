# 🎧 boAt Sales Dashboard (Power BI)

An interactive Power BI dashboard that analyses sales, profit, discounts, returns, and channel performance for **boAt** audio and wearable products across Indian cities and regions.

---

## 📌 Project Overview

This project turns raw sales data into a multi-page, interactive report. It helps answer questions such as:

- How much revenue, COGS, and profit is the business generating?
- Which cities, regions, and product categories drive the most sales and profit?
- How do festive seasons and weekends affect sales?
- Which sales channels (Amazon, Flipkart, boAt Official, etc.) sell the most?
- How much discount is given, and on which categories?
- Why are products being returned?

---

## 📊 Key Metrics (KPIs)

| KPI | Value |
|---|---|
| Total Revenue | 4.29bn |
| Total COGS | 3.65bn |
| Total Profit | 583.41M |
| Net Quantity | 1M |
| Net Weekend Sales | 290K |
| Net Discount Amount | 2.89bn |

---

## 🗂️ Report Pages

### Page 1 – Home / Sales Overview
- KPI cards: Total Revenue, Total COGS, Total Profit, Net Quantity, Net Weekend Sales
- **City-wise Sales** (Mumbai, Delhi, Bengaluru, Hyderabad, Chennai)
- **Net Sales by Category** (donut chart)
- **Sum of Net Sales by Region** (North, West, South, Central, East)
- **Festive Season Sales by Quarter** (line chart)
- Slicers: **Segment**, **Category**, **Region**

### Page 2 – Discounts, Channels & Festivals
- **Net Discount Amount** card
- **Quantity by Order Status** (Delivered / Returned / Cancelled)
- **City-wise Profit**
- **Quantity by Preferred Channel** (Amazon India, boAt Official, Croma, Flipkart, Local Multi-brand, Reliance Digital, Vijay Sales)
- **Discount % by Product Category**
- **Festival analysis table** (Big Festive Sale, Holi Sale, Independence Day Sale, Monsoon Deals, New Year Sale)
- **Net Sales by Launch Year** (2021–2025)
- Slicer: **Channel Name**

### Page 3 – Orders, Returns & City Performance
- **Region-wise Order Count** (pie chart)
- **Return Reasons** table (e.g., Changed mind, Sound imbalance, Charging defect, Connectivity issue, Defective unit, Display issue, Strap/fit issue)
- **City-wise Profit & Quantity** table with totals

### Tooltip Pages (Tooltips & Tooltips1)
Custom report-page tooltips that show extra detail on hover:
- **Tooltips1:** Sum of Profit, Sum of Quantity, Sum of Net Sales
- **Tooltips:** Sum of Discount Amount and Sum of Quantity by Category

---

## ✨ Features

- Multi-page report with **navigation buttons** between pages
- **Interactive slicers** (Segment, Category, Region, Channel Name)
- **Custom tooltip pages** for richer hover insights
- **Data modeling** with measures for revenue, COGS, profit, quantity, discounts, and weekend/festive sales
- Mix of KPI cards, bar, donut, pie, and line charts, plus detailed tables

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – report building and visualisation
- **Power Query** – data cleaning and transformation
- **DAX** – measures and calculated columns
- **Data Modeling** – relationships between fact and dimension tables

---

## 📁 Repository Structure

```
├── data modeling.pbix      # Power BI report file
├── data/                   # Source dataset(s)
├── screenshots/            # Dashboard images
└── README.md
```

> Update this structure to match your actual repository.

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Open the `.pbix` file in **Power BI Desktop**.
3. If prompted, update the data source path (**Home → Transform data → Data source settings**).
4. Click **Refresh** to load the data.
5. Use the slicers and navigation buttons to explore the report.

---

## 🖼️ Screenshots

| Home | Page 2 |
|---|---|
| ![Home](page1.png) | ![Page 2](page2.png) |

| Page 3 | Tooltips |
|---|---|
| ![Page 3](page3.png) | ![Tooltips](tooltips.png) |

> Add your screenshots to the `pages` folder and adjust the file names above.

---

## 💡 Insights

> Add your own findings here, for example:
> - Top-performing cities and regions
> - Best-selling product categories
> - Impact of festive sales on revenue
> - Most common return reasons

---

## 🔮 Future Improvements

- Add year-over-year and month-over-month trend analysis
- Add drill-through pages for city and product details
- Publish to Power BI Service with scheduled refresh
- Add mobile layout view

---

## 👤 Author

**Preetika Sharma**
• [GitHub](https://github.com/your-username)

---

⭐ If you found this project useful, consider giving it a star!
