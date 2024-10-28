# Flights
## Flight Data Analysis Project
### Overview :
This project aims to analyze flight data from a CSV file and perform various data cleaning, preprocessing, and visualization tasks.
The dataset includes information about flight schedules, delays, cancellations, and more.
The analysis explores trends and relationships between different delay factors and flight cancellations.

### Features :
-Data Preprocessing: Handling missing values, filling in relevant columns, and identifying cancelled and diverted flights.

-Cancellation Analysis: Identifying and categorizing flights based on various cancellation reasons and delays.

-Visualizations: Creating histograms, bar plots, and heatmaps for exploring trends in the dataset.

-Modeling: Logistic Regression and SVM (Support Vector Machine) for predicting flight cancellations.

### Libraries Used :
- pandas: Data manipulation and analysis.
- scikit-learn: Machine learning library for predictive modeling.
- matplotlib: Plotting basic visualizations.
- seaborn: Advanced visualizations and statistical plots.

### Project Structure :
flights.csv : Dataset file containing flight data
Flights_project.ipynb : Python script containing data analysis code
README.md : Documentation for the project

### How to Run:
1. git clone https://github.com/yourusername/Flights.git
2. Install the Required Packages:pip install pandas matplotlib seaborn scikit-learn
3. Run the Analysis Script:Flights_project.ipynb
4. Dataset:flights.csv

### Dataset:
The dataset (flights.csv) contains information about flights in the year 2015.
Key columns include: YEAR, MONTH, DAY, DAY_OF_WEEK, AIRLINE, FLIGHT_NUMBER,
       TAIL_NUMBER, ORIGIN_AIRPORT, DESTINATION_AIRPORT,
       SCHEDULED_DEPARTURE, DEPARTURE_TIME, DEPARTURE_DELAY, TAXI_OUT,
       WHEELS_OFF, SCHEDULED_TIME, ELAPSED_TIME, AIR_TIME, DISTANCE,
       WHEELS_ON, TAXI_IN, SCHEDULED_ARRIVAL, ARRIVAL_TIME,
       ARRIVAL_DELAY, DIVERTED, CANCELLED, CANCELLATION_REASON,
       AIR_SYSTEM_DELAY, SECURITY_DELAY, AIRLINE_DELAY,
       LATE_AIRCRAFT_DELAY, WEATHER_DELAY.

### Key Insights:
Trends by Month: Analyzing the distribution of flights across different months to identify seasonal trends.

Cancellation Reasons: Identifying and categorizing cancellation reasons based on multiple delay factors.

Diverted Flights: Exploring diverted flight counts using visualizations.

### Visualizations:
1- Histogram: Number of flights per month.

2- Count Plot:Number of flights that diverted.

3- Bar Plot: Distribution of cancellation reasons.

4- Heatmap: Total delay time for each airline by different delay factors.

### Contact:-
For any questions or feedback, feel free to contact me on my email : zinamarrie@gmail.com
  