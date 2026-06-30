# Predictive Maintenance Dashboard – Power BI Asset Health Project

This project is a Power BI dashboard built to explore how industrial sensor data can be used to support predictive maintenance, equipment risk monitoring and asset health reporting.

I developed this project to strengthen my experience with Power BI, Power Query and engineering-style data analysis. The dashboard uses industrial water pump sensor readings to identify equipment risk indicators and present the results in a clear, visual format for non-technical users.

## Project Overview

The dashboard analyses over **166,000 sensor readings** from industrial water pump equipment. The aim was to clean and structure raw sensor data, group equipment readings into risk bands, and identify which sensor values were most strongly linked to a decrease in Remaining Useful Life (RUL).

This project is designed to reflect the type of data analysis used in operational and maintenance environments, where data can support better decisions around equipment condition, asset health and maintenance prioritisation.

## Dashboard Preview

![Power BI Dashboard Overview](screenshots/dashboard_overview.png)

## Key Features

- Cleaned and prepared raw sensor data using **Power Query**
- Audited over **50 raw sensor variables** and removed non-predictive flat-lined sensors
- Created calculated risk bands to classify readings as **Healthy**, **Warning** or **Critical**
- Built KPI cards to show average Remaining Useful Life, lowest recorded RUL and total readings analysed
- Used trend charts and scatter plots to explore relationships between sensor readings and RUL
- Applied Power BI's **Key Influencers** feature to identify readings linked to equipment failure risk
- Presented findings in a clear dashboard format suitable for technical and non-technical audiences

## Main Findings

- The dataset contained **166,000+ sensor readings**
- **34.9%** of readings fell into the Critical risk band
- Key Influencers analysis highlighted specific sensor ranges linked to a decrease in Remaining Useful Life
- The dashboard helped translate large volumes of sensor data into clearer asset health insight

## Tools Used

- Power BI
- Power Query
- DAX / calculated columns
- Data cleaning
- Data visualisation
- Key Influencers analysis

## Skills Demonstrated

- Data cleaning and preparation
- Dashboard design
- Asset health and predictive maintenance analysis
- Working with large sensor datasets
- Interpreting equipment risk indicators
- Communicating technical findings clearly
- Turning raw operational data into practical insight

## Note

The full dataset and Power BI file are not included because of file size limitations. This repository includes a dashboard screenshot and a summary of the project approach, methods and findings.
