⚡ PowerForecast: AI-Based Electricity Demand Analysis
Predicting & Analyzing Electricity Demand for Delhi using AI & Data Science

📌 Project Overview
Electricity demand forecasting plays a crucial role in ensuring a stable power supply, reducing energy wastage, and optimizing power grid management. This project leverages historical electricity consumption data along with weather conditions to analyze power demand trends in Delhi.

🎯 Objectives
✔ Understand historical power consumption trends
✔ Identify peak demand hours and seasonal variations
✔ Explore the impact of weather conditions on demand
✔ Visualize insights using Power BI & Python
✔ Prepare a clean dataset for AI-driven forecasting models

📂 Dataset Information
Dataset Name: powerdemand_5min_2021_to_2024_with_weather.csv
Time Period: 2021 - 2024
Granularity: 5-minute intervals
Key Features:
Date & Time: Captures the timestamp of power demand
Power Demand (MW): Electricity consumption at each interval
Temperature (°C): Measures ambient temperature
Humidity (%): Atmospheric humidity levels
Wind Speed (km/h): Measures wind velocity
Day of the Week: Categorizes data into weekdays & weekends
🛠 Tech Stack
   Programming Language: Python
   Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly
   Visualization Tools: Power BI
   Version Control: Git & GitHub

📊 Exploratory Data Analysis (EDA)
EDA is crucial for understanding the dataset and extracting meaningful insights.

📌 Data Cleaning & Preprocessing
The dataset is cleaned and preprocessed by:
  Handling missing values and ensuring data consistency
  Converting datetime values for easier analysis
  Extracting new features such as hour, day of the week, and month

📌 Power Demand Trends Analysis
1) Identifying Peak Hours:
Electricity demand fluctuates throughout the day, with morning and evening peaks.
Peak demand is higher during summer evenings due to increased AC usage.
2) Seasonal Trends:
Power demand rises in summer and drops in winter.
Festivals and holidays show spikes or dips in demand.
3) Weather Impact on Power Consumption:
Higher temperatures lead to higher power usage (ACs, fans, cooling systems).
Humidity levels also influence electricity consumption, particularly in monsoons.
4) Weekday vs. Weekend Demand:
Weekdays have higher power demand compared to weekends.
Industrial and commercial sectors contribute significantly to weekday electricity consumption.

📂 Project Structure
📂 PowerForecast_Project  
│── 📁 data                  # Raw & cleaned datasets  
│── 📁 notebooks             # Jupyter notebooks for analysis  
│── 📁 visualizations        # Power BI dashboards & charts  
│── 📄 README.md             # Project documentation  
│── 📄 requirements.txt      # Dependencies for the project  





