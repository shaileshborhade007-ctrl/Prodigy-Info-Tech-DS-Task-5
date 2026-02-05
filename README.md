#  Task-05: Road Traffic Accident Analysis

##  Project Overview
This project focuses on analyzing road traffic accident data to identify important patterns related to **time of day, weather conditions, road surface conditions, lighting, and accident locations**. The goal is to understand key contributing factors that influence accident frequency and severity and to visualize accident hotspots.

This task is completed as part of the **Prodigy Infotech Data Science Internship**.

## Objective
- Analyze road traffic accident data
- Identify patterns related to:
  - Time of day
  - Weather conditions
  - Road surface conditions
  - Light conditions
  - Accident locations
- Visualize accident hotspots and contributing factors
- Draw meaningful insights to improve road safety

## Dataset
- **Dataset Name:** RTA Dataset (Road Traffic Accident Dataset)
- **File Used:** `RTA Dataset.csv`
- **Source:** Provided for internship task

## Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Methodology

### 1. Data Loading
- Loaded the dataset using Pandas
- Checked dataset structure, columns, and data types

### 2. Data Cleaning
- Handled missing values using mode-based imputation
- Removed inconsistencies
- Converted time column into proper datetime format

### 3. Feature Engineering
- Extracted hour from accident time
- Created a new feature: **Time of Day** (Morning, Afternoon, Evening, Night)

### 4. Exploratory Data Analysis (EDA)
- Analyzed accidents by time of day
- Studied weather conditions during accidents
- Examined road surface conditions vs accident severity
- Analyzed light conditions and their impact on severity
- Identified accident-prone areas and junction types

### 5. Data Visualization
- Bar charts
- Count plots
- Severity comparisons
- Hotspot analysis using area-based frequency

## Key Insights
- Most accidents occur during **evening and night hours**
- **Rainy and poor weather conditions** increase accident frequency
- **Wet and damaged road surfaces** contribute to higher accident severity
- **Poor lighting conditions** at night increase accident risk
- **Urban areas and junctions** are major accident hotspots
- 
## Conclusion
This analysis of the Road Traffic Accident (RTA) dataset was conducted to identify key patterns related to time of day, weather conditions, road surface conditions, lighting, and accident locations. The results show that traffic accidents occur most frequently during evening and night hours, which can be attributed to higher traffic volume, reduced visibility, and driver fatigue.
Weather conditions play an important role in accident occurrence, with a higher number of accidents reported during normal and rainy conditions. Rainy weather, combined with wet or uneven road surfaces, increases the likelihood of severe accidents due to reduced vehicle control. Additionally, accidents occurring under poor lighting or nighttime conditions tend to show greater severity,
highlighting the impact of visibility on road safety.The hotspot analysis indicates that urban areas and junctions such as crossroads and T-junctions experience a higher concentration of accidents. These locations involve frequent vehicle interactions, turning movements, and traffic conflicts, making them more prone to accidents.Overall, the findings suggest that improving road surface 
quality, street lighting, traffic management at junctions, and safety measures during peak hours can significantly reduce accident frequency and severity. This analysis provides valuable insights that can assist traffic authorities and policymakers in implementing targeted road safety strategies to minimize road traffic accidents.
