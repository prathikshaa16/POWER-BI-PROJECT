# 📊 POWER BI PROJECT  
**VIT Power BI Project**  

---

## 📂 What’s Inside  

# 🗳️ Indian General Election Result Analysis 2024  

An interactive **Power BI Dashboard** built using datasets from the **Indian General Elections 2024**, providing deep insights into **party performance, vote share, turnout, and constituency-wise results**.  

---

## 📊 Overview  

The **Election Analysis Dashboard** visualizes key election insights, including:  

* 🪧 Seats won by each party & alliance  
* 📊 Vote share (%) distribution across states and nationally  
* ⚖️ Margin of victory and close contests  
* 🗺️ Geographic spread of results by state & constituency  
* 👥 Candidate-level details and turnout patterns  
* 🔁 Statewise aggregation and comparison  

It allows users to **filter by state/party**, **analyze swings**, and **drill down to constituency level** — all within a clean, interactive interface.  

---

## ⚙️ Data Source and Preparation  

### **Files Used**
- `constituencywise_results.csv`  
- `constituencywise_details.csv`  
- `partywise_results.csv`  
- `statewise_results.csv`  
- `states.csv`  
- `Indian General Election Result Anlaysis.pbix`  

### **Data Transformation (Power Query)**  
- Imported all CSV files using **Get Data > Text/CSV**.  
- Expanded nested details (candidates, votes, parties).  
- Cleaned and standardized column names (`Constituency_ID`, `Party`, `Votes`, `Turnout`).  
- Created calculated columns (e.g., `VoteShare`, `Margin`).  
- Removed duplicate/unnecessary metadata columns.  

### **Relationships**  
- **States → Constituencies → Candidates** (hierarchical model).  
- **Partywise Results** linked with state and constituency data.  
- Cross-filtering enabled across **State**, **Party**, and **Constituency**.  

---

## 🧮 DAX Measures  

[DAX Measures](DAX%20MEASURES.docx)

---

## 📈 Key Visualizations  

| **Section**              | **Objective**                        | **Visualization Type**   | **Highlights** |
|---------------------------|--------------------------------------|--------------------------|----------------|
| 🧾 National Summary       | Seats & vote share by party          | KPI Cards + Bar Chart    | Seat count, vote % |
| 🗺️ Map (Results)          | Display winners by constituency/state | Shape Map                | Party-colored, tooltips with margin |
| 📊 Party Performance      | Compare vote shares & seats          | Treemap + Bar Chart      | Filterable by state |
| 📅 Statewise Results      | Seat & vote breakdown per state      | Matrix + Bar Chart       | Regional analysis |
| ⚖️ Margin Analysis        | Identify close contests              | Bar / Scatter Plot       | Highlights seats won by <2% |
| 👥 Candidate Drilldown     | Candidate-wise details               | Table + Conditional Formatting | Winner vs runner-up |
| 👥 Turnout Analysis       | Voter participation                  | Line / Area Chart        | State-level turnout % |

---

## 🎨 Dashboard Design  

- **Theme:** Clean dark/light hybrid with saffron/green highlights  
- **Layout:**  
  - **Top:** National KPIs (Seats, Vote Share, Turnout)  
  - **Left:** State & Party slicers  
  - **Center:** Map + Party performance charts  
  - **Right:** Margin analysis, turnout, candidate drilldown
- **Interactivity:**  
  - Drillthrough to candidate profiles  
  - Filters for state, party, and alliance  
  - Conditional formatting on vote share & margins  

---

## 🧰 Tools & Technologies  

| **Tool / File**              | **Purpose** |
|-------------------------------|-------------|
| **Power BI Desktop (.pbix)** | Data modeling & visualization |
| **CSV Files**                 | Election datasets (constituency, state, party) |
| **Power Query Editor**        | Data cleaning & transformation |
| **DAX**                       | Custom measures (Vote Share, Margin, KPIs) |

---

## 🎯 Skills Demonstrated  
- Structuring datasets for analysis  
- Building **table relationships**  
- Writing calculated columns & measures in **DAX**  
- Applying slicers for **interactive filtering**  
- Designing clean, interactive **dashboards**  

---

## ⚡ How to Use  
1. Clone or download this repository  
2. Open the `.pbix` file in **Power BI Desktop**  
3. Explore dataset, model, and report pages  
4. Interact with slicers, bookmarks, and tooltips to test functionality  

---

## 🚀 Future Enhancements  

1. 🗓️ Add historical elections data for swing analysis.  
2. 📡 Live updates (if EC data feed is available).  
3. 🔮 Predictive analytics — Forecast future seat distributions.  
4. 🛰️ Regional polarization heatmaps.  
5. 📱 Mobile-optimized view for Power BI Mobile app.  

---

## 🧾 Summary  

The **Indian General Election Result Analysis 2024 Dashboard** demonstrates how to transform raw election datasets into **actionable political insights**.  

It enables **comparisons across states & parties**, **drilldowns to candidate level**, and **clear visualization of voter behavior** — all within a professional Power BI environment.  

> 💡 *This project represents end-to-end Power BI development using real election datasets — from data preparation and DAX modeling to dashboard storytelling.*

---

## 📂 Project Files  

- [Indian General Election Result Anlaysis.pbix](Indian%20General%20Election%20Result%20Anlaysis.pbix)
- [DAX Measures Documentation](DAX%20MEASURES.docx)
  
---

## 📜 License  
This project is licensed under a **custom restrictive license**.  
You may **view** and **reference** the code for educational purposes, but redistribution or commercial use is **prohibited without permission**.

---
