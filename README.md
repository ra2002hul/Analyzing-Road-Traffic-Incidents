🚦 Dhaka Road Traffic Accident Analysis (2007–2021)


📌 Project Overview
Road traffic accidents cause severe loss of life, injuries, and economic damage, making road safety a critical public concern.
This project analyzes road traffic accident data from Dhaka (2007–2021) to identify patterns, hotspots, risk factors, and trends that contribute to accidents and fatalities.
The insights aim to support traffic authorities and policymakers in implementing data-driven safety measures to reduce accidents and fatalities.

🏷️ Domain
Transportation Safety & Road Accident Analysis

📂 Dataset Information


Dataset Name: Bangladesh Road Traffic Accident Dataset


Source: Figshare (Multi-source integrated dataset)


Coverage Area: Urban Dhaka & Highways


Time Period: 2007 – 2021


Total Records: 47,680 accidents


Original Columns: 31


Final Columns (after feature engineering): 39



🧾 Key Column Categories


Location Details – District, area, road name, landmarks


Time Information – Date, time, year, month


Accident Severity – Death count, injury count


Road & Junction Details – Junction type, road type, condition


Traffic Control Factors – Signals, dividers, signs


Environmental Conditions – Weather, lighting, visibility



🛠️ Tools & Technologies


Python


Google Colab


Libraries Used:


Pandas


NumPy


Matplotlib


Seaborn





🔄 Project Workflow
Stage 1: Initial Data Exploration


Loaded Excel dataset into Pandas DataFrame


Verified structure: 47,680 rows × 31 columns


Checked:


Data types


Null values (0% missing)


Duplicate records (minimal, ignored)




Key Observations


Dataset quality is exceptionally clean


Date & time columns contain inconsistent formats


Suitable for detailed cleaning and feature engineering



Stage 2: Data Cleaning & Preprocessing


Standardized column names (snake_case)


Converted mixed date formats using pd.to_datetime()


Standardized time formats into 24-hour format


Engineered new features:


hour_of_day


peak_hour (Rush vs Off-peak)


has_fatalities


risk_category


accident_type




Cleaned categorical text fields (weather, lighting, junction types)


Final Cleaned Dataset


Rows: 47,680


Columns: 39


No rows dropped



Stage 3: Exploratory Data Analysis (EDA)
📊 Statistical Insights


Fatal accidents: 11,717 (24.6%)


Non-fatal accidents: 35,963 (75.4%)


Peak hour accidents: 38%


Average deaths per accident: 1.0


Most common driver age: 24 (96% of cases)


📈 Trend Analysis


Accident growth rate: +12% per year


COVID impact: Dip in 2020, sharp rebound in 2021


2021 peak: 4,935 accidents


📍 Hotspot Analysis


Top 5 hotspots contribute 45% of total accidents


Rainbow Crossing identified as the most dangerous location


🌦️ Risk Factors Identified


Dusk lighting: 28% of all accidents


Rainy + wet roads: 4× higher risk


Pedestrians: 45% of victims


3-way junctions: 65% of accidents



Stage 4: Key Findings & Insights
🔑 Descriptive Insights


Total accidents: 47,680


Fatality rate: 1 in 4 accidents


Deadliest time: Dusk


Primary victims: Pedestrians


Riskiest driver group: Age 24–26


🔍 Diagnostic Analysis (Why?)


Poor lighting during dusk hours


Lack of pedestrian infrastructure


Speeding and inexperience among young drivers


Poor road conditions during monsoon


🔮 Predictive Analysis (What’s Next?)
If current trends continue:


2022: ~5,527 accidents


2025: ~7,300 accidents


2027: ~9,200 accidents (50% increase)



🛑 Recommendations (Prescriptive Analysis)
🚨 Priority 1: Hotspot Management


Signalize major junctions (e.g., Rainbow Crossing)


Build foot-over bridges


Improve roundabout design


🌆 Priority 2: Dusk Safety Measures


Increase police patrols (6–8 PM)


Install solar-powered streetlights


Restrict heavy vehicle movement during rush hours


🚶 Priority 3: Pedestrian Protection


Zebra crossings & rumble strips


Clear encroachments on footpaths


Speed cameras near schools


📊 Monitoring


Real-time accident tracking dashboard using Power BI



📌 Final Key Insights


Hotspot concentration: Fixing top 5 locations can reduce 45% accidents


Time vulnerability: Dusk is the deadliest period


Victim profile: Pedestrians need urgent infrastructure support


Weather impact: Rain multiplies accident risk


Driver risk: Young drivers (24–26) dominate accident statistics


Future risk: Accidents will continue rising without intervention



✅ Conclusion
This project demonstrates how data analytics and visualization can uncover critical road safety issues and support evidence-based decision-making.
Targeted interventions at high-risk locations, times, and populations can significantly reduce accidents and fatalities.
