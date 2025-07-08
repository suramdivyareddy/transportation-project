# NYC Motor Vehicle Collisions Analysis

## Project Overview

![Uploading nycposter.png…]()

This project provides a comprehensive data analysis of the Motor Vehicle Collisions dataset sourced from NYC Open Data. The objective is to identify key patterns, risk factors, and trends in traffic accidents across New York City. By leveraging various data analysis and visualization techniques, the project aims to generate actionable insights that can inform road safety initiatives for all road users, including drivers, cyclists, and pedestrians.

## Dataset

* **Name:** Motor Vehicle Collisions - Crashes
* **Source:** [NYC Open Data](https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95)
* **Description:** This dataset contains details of police-reported motor vehicle collisions in NYC. Each record corresponds to a unique crash event and includes information on location, time, contributing factors, vehicle types, and the number of persons injured or killed.

## Analysis Highlights

The project explores the dataset through several analytical lenses:

* **Temporal Analysis:** Investigated how crash frequencies change over time. This includes identifying peak hours during the day, monthly variations, and long-term trends. A key finding was the significant dip in crashes during the 2020 COVID-19 pandemic.
* **Geospatial Analysis:** Mapped collision data to pinpoint high-risk locations. Analysis by borough, along with heatmaps and severity maps, revealed that Manhattan and Brooklyn have the highest concentration of crash incidents.
* **Contributing Factor Analysis:** Identified the primary causes of accidents, with "Driver Inattention/Distraction" being the most common factor. The analysis also highlighted the vehicle types most frequently involved, such as sedans and SUVs.
* **Comparative Analysis:** A deep-dive comparison of accident patterns on weekdays versus weekends was performed. This revealed distinct hourly trends, with weekday crashes peaking during commute times and weekend crashes peaking late in the evening.

## Key Insights & Visualizations

* **Peak Crash Time:** The highest frequency of crashes occurs during the evening rush hour, between 3 PM and 6 PM.
* **Highest Risk Boroughs:** Brooklyn and Manhattan show the highest density of collisions.
* **Primary Cause:** The most cited contributing factor to crashes is driver inattention and distraction.
* **Visualizations:** The analysis is supported by a variety of visualizations, including bar charts, line plots, heatmaps, and geospatial maps created with `folium`.

## Tools and Libraries

This project was conducted in Python using the following core libraries:
* **pandas:** For data manipulation and cleaning.
* **matplotlib & seaborn:** For data visualization.
* **statsmodels:** For time series decomposition.
* **folium:** For creating interactive geospatial maps.

## How to Use

The complete analysis is contained within the `NYC_Motor_Vehicle_Collision_Analysis.ipynb` Jupyter Notebook. To run the analysis:

1.  Ensure you have the required Python libraries installed.
2.  Download the dataset `Motor_Vehicle_Collisions_-_Crashes_20250104.csv` from NYC Open Data.
3.  Update the file path in the notebook to point to the location of your dataset.
4.  Execute the cells sequentially to reproduce the analysis.

## Recommendations for Road Safety

Based on the analysis, the following recommendations are proposed:

1.  **Launch Targeted Awareness Campaigns:** Focus on the dangers of distracted driving, especially during weekday evening commutes.
2.  **Prioritize Hotspot Interventions:** Allocate resources for engineering and safety improvements in high-crash zones within Manhattan and Brooklyn.
3.  **Implement Dynamic Enforcement Strategies:** Adjust traffic enforcement schedules to align with peak crash times, which differ significantly between weekdays and weekends.
4.  **Improve Data Collection Standards:** Enhance data quality through standardized reporting for vehicle types and more complete location information to enable more granular and accurate future analyses.
