# Flight-Price-EDA-Feature-Engineering-

✈️ Overview

This is a mini project to show how I perform data cleaning and feature engineering in Python.
I used a flight dataset from Kaggle and extracted useful features like date, time, and duration, converting them into numeric values for easy analysis and modeling.

📊 Dataset Summary

Original Columns:

Airline, Date_of_Journey, Source, Destination, Route, Dep_time, Arrival_time,
Duration, Total_Stops, Additional_Info, Price


Final Columns (after Feature Engineering):

Airline, Source, Destination, TotalStops, AdditionalInfo, Price,
Date, Month, Year, ArrivalHour, ArrivalMin, Dep_hour, Dep_min,
Duration_hour, Duration_min

⚙️ Key Steps Performed

Date Splitting

Extracted Date, Month, and Year from Date_of_Journey

Converted them to integer type

Time Feature Extraction

From Dep_time: derived Dep_hour, Dep_min

From Arrival_time: derived ArrivalHour, ArrivalMin

From Duration: derived Duration_hour, Duration_min

Categorical to Numeric Conversion

Converted Total_Stops values (e.g., 'non-stop', '1 stop') into numeric form

Data Cleaning

Dropped unnecessary columns (Route, original time/date columns)

Fixed data types and handled missing values

Final Output

Created a clean dataset ready for model training

No visualizations or ML models — purely EDA & preprocessing

🧰 Tools & Libraries

Pandas — for data cleaning, manipulation, and transformation

NumPy — for numeric computations and type conversion

🎯 Objective

To showcase my ability to perform data preprocessing and feature engineering — converting unstructured raw data into a model-ready structured dataset using Python.
