# ☕ Starbucks Nutrition & Store Analysis — Power BI Dashboard

An interactive Power BI dashboard that analyzes the nutritional profile of Starbucks beverages (calories, sugar, caffeine, protein) and, optionally, the global footprint of Starbucks stores.

> **Built by:** Sunil Luhar — MIS & Data Reporting | Power BI • Excel • SQL • Looker Studio
> **Live dashboard:** [Click here to view](PASTE-YOUR-POWER-BI-PUBLISH-TO-WEB-LINK-HERE)

---

## 📸 Dashboard Preview

![Dashboard Page 1](screenshots/page1.png)

<!-- Delete the next line if you do not build a store page -->
![Dashboard Page 2](screenshots/page2.png)

---

## 🎯 Project Objective

To turn raw Starbucks menu data into a clean, easy-to-read dashboard that helps a business user quickly answer questions such as:

- Which beverage categories have the highest calories, sugar and caffeine?
- How do size and milk choice change the nutrition of a drink?
- Which drinks fit a lighter, lower-sugar preference?
- Where are Starbucks stores located and how are they owned? *(Store page)*

---

## 📊 Key Features

- **KPI cards:** Total Beverages, Average Sugar, Average Calories, Average Caffeine
- **Category analysis:** Stacked area chart (avg calories), donut chart (beverage count) and column chart (avg caffeine) by beverage category
- **Beverage-level view:** Bar chart of average caffeine by individual beverage
- **Interactive filters:** Protein slicer and Beverage Preparation (size / milk type) slicer
- **Custom design:** Category icons, themed layout and text insights

---

## 🔎 Sample Insights

- The **Coffee** category has the highest average caffeine, at roughly **294 mg** per serving.
- **Classic Espresso** drinks average about **122 mg** of caffeine, while Frappuccino and Iced Beverages sit around **99–102 mg**.
- The menu data covers **9 beverage categories** and **242 beverage / size / preparation combinations**.

*(Add your own 2–3 insights here after exploring the filters.)*

---

## 🗺️ Store Analysis Page *(keep this section only if you build Page 2)*

Using the global store directory (**25,600+ store records across 73 countries**):

- The **United States** has the most stores (**13,608**), followed by **China (2,734)** and **Canada (1,468)**.
- Ownership mix: **Company Owned (11,932)**, **Licensed (9,375)**, **Joint Venture (3,976)** and **Franchise (317)**.
- Map visual built from store latitude and longitude, with country, state and city slicers.

---

## 🛠️ Tools & Skills Used

| Area | Details |
|---|---|
| Tool | Microsoft Power BI Desktop |
| Data preparation | Power Query (cleaning column names, fixing data types, splitting size and milk type) |
| Calculations | DAX measures (total beverages, average sugar, average calories, average caffeine) |
| Visuals | Cards, stacked area, donut, column and bar charts, slicers, images and text boxes |
| Design | Custom layout, icons and consistent color theme |

---

## 📁 Repository Structure

```
starbucks-powerbi-dashboard/
│
├── starbucks_dashboard.pbix      # Power BI report file
├── data/
│   ├── starbucks.csv             # Beverage nutrition data
│   └── directory.csv             # Global store directory
├── screenshots/
│   ├── page1.png
│   └── page2.png
└── README.md
```

---

## ▶️ How to Open the Dashboard

1. Download or clone this repository.
2. Install **Power BI Desktop** (free) from Microsoft.
3. Open `starbucks_dashboard.pbix`.
4. If Power BI asks for the data source, go to **Home → Transform data → Data source settings** and point it to the CSV files in the `data/` folder.

---

## 📂 Data Sources

- **starbucks.csv** — nutritional values for Starbucks beverages (calories, fat, carbohydrates, sugar, protein, caffeine, etc.) by category, size and preparation.
- **directory.csv** — list of Starbucks store locations with country, city, ownership type and coordinates.

Both datasets are publicly available and used here for learning and portfolio purposes.

---

## 📬 Contact

Available for freelance Power BI, Excel and reporting projects.

- **Name:** Sunil Luhar
- **LinkedIn:** [www.linkedin.com/in/sunil-luhar-b7ab69383]
- **Upwork:** [add your link](https://www.upwork.com/freelancers/~012da964e093fca48f]
- **Email:** [luharsunil965@gmail.com]
