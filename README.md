# Energy Output and Solar Plant Reliability
<img width="1188" height="553" alt="image" src="https://github.com/user-attachments/assets/b8ef4acf-42d5-491e-bdca-815fabc796a7" />
📌 Project Overview

This project replicates the type of analysis done in real-world energy analyst roles at companies like Tesla.
I built a fully interactive Excel dashboard to evaluate the performance and reliability of two solar plants using a 34-day dataset.

The dashboard helps answer critical business and engineering questions:

How much energy was produced? (KPIs: Total, Daily Avg, Peak Power)

How efficient were the plants? (Performance Ratio Proxy)

How reliable were the assets? (Zero-Output Events, Availability vs Downtime)

What external factors drove dips in performance? (Temperature, Time-of-Day patterns)

Which inverters need attention? (Top & Bottom 10 Source Keys)

----
📊 Dashboard Features

✅ Key KPIs

Total Energy Produced (kWh)

Average Daily Energy (kWh/day)

Peak Power (kW)

Performance Ratio Proxy (%)

Zero-Output Events

Average Module Temperature (°C)

Availability % vs Downtime %


----
✅ Visuals & Insights

📈 Daily Energy Trend (dips and outages)

⏰ Hourly Energy Profile (bell curve)

🌡️ Temperature Impact on Output

🔧 Top & Bottom 10 Inverters (asset health)

📊 Cumulative Month-to-Date (MTD) Energy

----

✅ Interactive Slicers

Filter by Plant

Filter by Month (May/June)

Filter by Weekday

🛠️ Skills Demonstrated

Excel: PivotTables, Slicers, Conditional Formatting, KPI Tiles

Formulas:

IF / Nested IF → fault detection (e.g., Zero AC under daylight)

AVERAGEIF / AVERAGEIFS → efficiency checks

VLOOKUP, XLOOKUP, INDEX-MATCH → equipment metadata mapping

Grouping & Binning (Temperature analysis)

Percent calculations (Availability & Downtime)

Critical Thinking: Linked solar performance with real-world causes (soiling, clipping, shading, derating)

Data Cleaning: Removed invalid nighttime outputs, fixed missing intervals

📸 Dashboard Preview


(Interactive Excel dashboard with KPI tiles, trend analysis, and inverter-level health checks)

📂 Files in Repository

Solar_Plant_Data.xlsx → Full Excel dashboard

Calculations_Sheet.xlsx → Helper formulas and KPI logic

README.md → Project documentation

🚀 Key Takeaways

Plant 1 consistently outperformed Plant 2 in both daily and hourly profiles.

Performance Ratio Proxy averaged ~30%, indicating room for efficiency improvements.

Zero-output events flagged ~8,200 daylight intervals (~11% downtime).

Higher module temperatures showed derating behavior, confirming thermal impacts.

Bottom 10 inverters (from Plant 2) highlight likely maintenance candidates.

----

📌 Why This Project?

Energy is at the heart of sustainability. This project gave me the opportunity to:

Apply data analytics to renewable energy

Build an analyst-ready dashboard for decision-making

Simulate the role of a Tesla Energy Analyst with real KPIs and visuals
https://www.kaggle.com/datasets/anikannal/solar-power-generation-data
