# Analyzing-Yellow-Taxi-Trip-Data-Statistical_Analysis

**Project Overview**
This project analyzes the NYC Yellow Taxi Trip Dataset for January 2024 to uncover key insights into passenger payment preferences, trip characteristics, and fare dynamics. By utilizing data preprocessing, visualization, and hypothesis testing, the study aims to provide actionable insights into how payment types (cash vs. card) influence fare amounts and trip distances.

**Objectives**
To clean and preprocess the data by handling missing values, duplicates, and outliers.
To explore the relationships between trip attributes like fare amount, trip distance, and payment type.
To conduct hypothesis testing to identify significant differences in fare amounts based on payment types.
To provide data-driven recommendations for optimizing operations and enhancing passenger experience.

**Dataset**
The dataset used for this project includes detailed trip-level information such as:
Pickup and Dropoff Timestamps (tpep_pickup_datetime, tpep_dropoff_datetime)
Trip Distance (trip_distance)
Passenger Count (passenger_count)
Fare Amount (fare_amount)
Payment Type (payment_type)
Other variables include location IDs, rate codes, surcharges, and tips.

**Methodology**
**Data Loading and Cleaning:**
Imported the dataset into a pandas DataFrame.
Processed and cleaned the data by removing missing values, handling outliers, and ensuring valid entries.

**Exploratory Data Analysis (EDA):**
Analyzed distributions of trip distances, fare amounts, and payment types.
Created visualizations to identify patterns and trends in the data.

###Hypothesis Testing:

**Null Hypothesis (H₀):** There is no significant difference in fare amounts between cash and card payments.
**Alternative Hypothesis (H₁):** There is a significant difference in fare amounts between cash and card payments.
Conducted a two-sample t-test, resulting in:
T-Statistics: 149.05
P-Value: 0.0 (indicating a statistically significant difference).

**Results and Recommendations:**
Card payments are more common for higher fare amounts and longer trips.
Cash payments are typically used for shorter trips with lower fares.
Recommendations include incentivizing card payments to streamline operations and improve customer convenience.

**Results**
Significant Findings:
**The hypothesis test confirmed a significant difference in fare amounts based on payment methods. Card payments are more prevalent for longer and higher-fare trips.**

**Visual Insights:**
Distribution of fare amounts and trip distances by payment type.
Payment type trends influencing customer behavior and fare dynamics.

