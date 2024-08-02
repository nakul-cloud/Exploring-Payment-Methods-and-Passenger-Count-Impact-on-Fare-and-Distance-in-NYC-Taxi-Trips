# Exploring-Payment-Methods-and-Passenger-Count-Impact-on-Fare-and-Distance-in-NYC-Taxi-Trips
# Overview
This project explores the relationship between different payment methods and the associated fare amounts and trip distances in NYC taxi trips. The data was cleaned and analyzed to understand how these variables are distributed and related.


# Prerequisites
To run the analysis, you will need the following Python packages:

pandas
matplotlib
seaborn
scipy
plotly
statsmodels
Data Source
The dataset used in this analysis is yellow_tripdata.csv, which contains information about taxi trips, including pickup and dropoff times, passenger counts, trip distances, and payment details.

# Files
yellow_tripdata.csv: The raw data containing NYC taxi trip records.

#Dataset source: https://data.world/vizwiz/nyc-taxi-jan-2020/workspace/file?filename=yellow_tripdata_2020-01.csv

analysis.ipynb: The Jupyter Notebook containing data cleaning, analysis, and visualizations.
README.md: This file, providing an overview of the project, key findings, and instructions.

# Key Findings
Card payments dominate the payment methods for NYC taxi trips.
Trips paid by card tend to have higher fares and longer distances on average compared to cash payments.
The data required cleaning to remove outliers and erroneous entries.

# How to Run
Open the Jupyter Notebook analysis.ipynb ,load dataset and run the cells to view the analysis and results.

# Steps
Data Loading:
Load the dataset using pandas.

Data Preprocessing:

Convert date columns to datetime format.
Calculate the trip duration.
Handle missing values and filter relevant data.
Remove duplicate entries.
Exploratory Data Analysis (EDA):

Visualize distributions of fare amounts, trip distances, and trip durations.
Analyze the distribution of passenger counts and payment types.
Calculate and visualize statistics related to different payment types.
Outlier Detection and Handling:

Identify and remove outliers in fare amounts, trip distances, and trip durations.
Visualizations:

Histograms for fare amount and trip distance distributions by payment type.
Bar plots for mean trip distances and mean fare amounts by payment type.
Pie charts for the distribution of payment types.
# Usage
To run the analysis, ensure you have all required packages installed and execute the Jupyter notebook. The visualizations will provide insights into various aspects of the taxi trips.




# Conclusions:
Distribution of Payment Types: The majority of taxi rides were paid using cards, followed by cash and other payment methods. This indicates a preference for cashless transactions among passengers.

Fare Amounts by Payment Type: The average fare amount for card payments was slightly higher than for cash payments. This could suggest that passengers using cards might have taken longer trips or that card payments are more common for higher fare trips.

Trip Distance by Payment Type: The mean trip distance for card payments was observed to be longer compared to cash payments. This could imply that passengers paying by card might be more likely to take longer trips.

Passenger Count Distribution: The analysis revealed that most taxi trips had a passenger count of one, with a gradual decrease in frequency as the passenger count increased. Trips with zero passengers were likely erroneous data points.

Data Cleaning and Outliers: The data contained some outliers and negative values for fare amount, trip distance, and duration, which were removed for accurate analysis. The cleaned dataset provided more reliable insights into the trends.

# Acknowledgements
This project is conducted using publicly available yellow taxi trip data.

# Contact
For any inquiries or issues, please contact Nakul Jadhav at jadhavnakul456@gmail.com.





