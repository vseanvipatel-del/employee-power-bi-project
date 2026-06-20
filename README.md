# employee-power-bi-project
# 📊 Employee Performance & Utilization Analysis

This repository contains an Exploratory Data Analysis (EDA) and Business Intelligence (BI) project focused on monitoring workforce productivity, operational utilization, and regional client coverage patterns. Using a transactional employee log dataset, this project provides a clear breakdown of resource allocation by evaluating logged baseline capacities against real revenue-generating output.

## 📌 Project Overview
Maximizing resource utilization while maintaining client satisfaction is a core operational challenge in service delivery. This analysis diagnoses corporate efficiency gaps across multiple regional branches. By analyzing total logged hours versus actual billable hours alongside client fulfillment metrics, this project helps corporate stakeholders spot low-utilization areas, reward top performers, and optimize regional staffing distribution.

---

## 📊 Dataset & Architecture
The project pipelines analyze a multi-dimensional workforce database across the following attributes:

* **Primary Source Log:** `Employee_data.csv`
* **Operational Variables:**
  * **Employee Identity:** `Name`
  * **Branch Demographics:** `Location` (Branches A, B, C, and D)
  * **Capacity Markers:** `Total Hours` logged vs. revenue-generating `Billable Hours`
  * **Client Coverage:** `Clients Assigned` vs. `Clients Seen`

---

## 🔍 Core Operational Benchmarks Established

The data models establish the following platform-wide benchmarks:
* **Total Resource Capacity:** **31,823** operational hours logged by the workforce.
* **Billable Output:** **15,712** hours executed on direct client projects.
* **Global Resource Utilization Rate:** **49.37%** average billable efficiency.
* **Client Engagement Success:** **16,028** successful client interactions achieved.
* **Unseen Client Ratio:** **32.98%** client coverage friction gap.

### 📍 Key Regional Takeaways
* **Volume Load:** **Location A** faces the heaviest operational assignment load, tracking a footprint of 6,016 assigned clients.
* **Fulfillment Efficiency:** **Location B** demonstrates the highest localized branch coverage, successfully engaging 4,027 seen clients out of 5,596 assigned.

---

## 📁 Repository Directory

* 📄 **`Employee_data.csv`**: The raw comma-separated transactional database containing logged employee work entries.
* 📊 **`DASH.pbix`**: The master Power BI Desktop workspace file containing relational data models, custom star-schema metrics, and automated DAX slicers.
* 📕 **`Final_Dashboard.pdf`**: An executive-ready PDF report printout showing the complete visual performance and utilization dashboard canvas for quick review.

---

## 🛠️ Tech Stack & Requirements
To run the analytical code cells or reproduce the visual charts, set up a Python 3.9+ environment with the following dependencies:
* **Pandas** (Data engineering and metrics grouping)
* **NumPy** (Mathematical array math)
* **Matplotlib & Seaborn** (Workforce engagement curves and branch bar charts)

Install requirements via `pip`:
```bash
pip install pandas numpy matplotlib seaborn jupyter
