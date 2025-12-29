Deloitte Data Analytics Virtual Internship
This repository contains my completed projects for the Deloitte Data Analytics Virtual Internship via Forage. These tasks simulate real-world data analyst responsibilities, ranging from telemetry data visualization to corporate social responsibility (CSR) reporting.

🚀 Project Overview
Task 1: Manufacturing Downtime Analysis (Tableau)

Objective: Analyze Daikibo’s manufacturing telemetry data to identify downtime trends across different global factories.


Data Processing:

Imported complex JSON telemetry data into Tableau, configuring schema levels for analysis.


Developed a Calculated Field named Unhealthy using the formula: IF [Status] = "unhealthy" THEN 10 ELSE 0 END.


This logic accounts for 10-minute message intervals to quantify total downtime for various manufacturing processes.

Visualization:

Built interactive bar charts showing Downtime Per Factory and Downtime Per Machine Type.


Created a synchronized Executive Dashboard with "Use as Filter" functionality, allowing users to select a factory and instantly see the downtime breakdown by specific machines (e.g., Laser Cutters, Furnaces).


Task 2: Employee Compensation Equality Classification (Excel/Python)
Objective: Process employee compensation data to monitor and report on corporate equality standards across various job roles.

Logical Modeling:

Engineered a new feature, Equality class, to categorize "Equality Scores" (ranging from -100 to +100).

Implemented a three-tier classification system:

Fair (+-10): Scores indicating balanced compensation.

Unfair (<-10 AND >10): Scores showing moderate discrepancy.

Highly Discriminative (<-20 AND >20): Scores requiring immediate corporate attention.

Outcome: Delivered an edited Equality Table.xlsx providing clear, actionable segments for HR and leadership.

🛠️ Tools & Technologies
Data Visualization: Tableau Desktop (Dashboarding, Calculated Fields, Interactivity)

Data Engineering: Excel (Logic Formulas) / Python (Pandas for data transformation)

Data Formats: JSON (Telemetry), XLSX (Compensation Data)
