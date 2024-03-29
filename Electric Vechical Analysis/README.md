# Electric Vehicle Population Data Analysis

#### By: [Shakti Singh](https://www.linkedin.com/in/shakti--singh/)


## Introduction
Within this project, we delve into an extensive dataset teeming with information concerning electric vehicles. This dataset encompasses an array of attributes, including VIN, City, State, Model Year, Make, Model, Electric Vehicle Type, Electric Range, Base MSRP, and a host of other pertinent details. The primary aim of this analysis is to extract valuable insights and cultivate a comprehensive understanding of the distinctive traits that define the electric vehicles cataloged within the dataset.

## Data Overview
The dataset contains 135,039 entries with 17 columns. Some columns have missing values, such as "County," "Model," "Legislative District," "Vehicle Location," and "Electric Utility." These missing values will need to be handled during data preprocessing.


## Features Interpretability
1. VIN (1-10): Partial vehicle identification number consisting of the first 10 digits.
2. County: The county where the vehicle is registered.
3. City: The city where the vehicle is registered.
4. State: The state where the vehicle is registered.
5. Postal Code: The postal code of the vehicle registration location
6. Model Year: The year the vehicle was manufactured.
7. Make: The manufacturer or brand of the vehicle.
8. Model: The specific model of the vehicle.
9. Electric Vehicle Type: Indicates whether the vehicle is a Battery Electric Vehicle (BEV) or a Plug-in Hybrid Electric Vehicle (PHEV).
10. Clean Alternative Fuel Vehicle (CAFV) Eligibility: Indicates if the vehicle is eligible for Clean Alternative Fuel Vehicle benefits.
11. Electric Range: The range of the vehicle on a full electric charge.
12. Base MSRP: The manufacturer's suggested retail price for the vehicle.
13. Legislative District: The legislative district associated with the vehicle registration location.
14. DOL Vehicle ID: Unique identifier assigned by the Washington State Department of Licensing.
15. Vehicle Location: The precise location of the vehicle.
16. Electric Utility: The electric utility company associated with the vehicle.
17. 2020 Census Tract: The census tract where the vehicle is registered.


## Data Collection
Collected the dataset from Kaggle website 
 - Link to the data source: (https://www.kaggle.com/datasets/rajkumarpandey02/electric-vehicle-population-data)

## Data Understanding
Conducted an in-depth exploration of the dataset's structure, comprehensively documenting available columns, data types, and referring to the data dictionary for clarification.

## Data Pre-processing and Cleaning
I improved the dataset's quality through a series of data cleaning techniques to prepare the dataset for analysis:

- Employed strategies such as addressing missing data by considering the type of information that was missing.
- Optimized performance by converting specific columns to their appropriate data types.

## Feature Engineering
Created new variables from existing data that provided additional insights.

## Exploratory Data Analysis (EDA)
Exploratory data analysis involves addressing the questions and objectives defined within the scope of this project.

## Descriptive Statistics
The descriptive statistics reveal that the "Electric Range" exhibits a broad range of values, spanning from 0 to 337, with an approximate mean value of 72.3. Likewise, the "Base MSRP" column also displays a wide range of values, with an approximate mean of 1404.82.

## Data Visualization
I employed a range of data visualization techniques to delve into the connections among distinctive features and uncovered any discernible trends or patterns within the dataset. These visualizations took the form of bar plots, histograms, box plots, and scatter plots, enabling us to grasp the dataset more comprehensively.


## Conclusion
Exploring the data yielded valuable insights into the electric vehicle population data. I uncovered the distribution of various features, pinpointed correlations, and unveiled underlying patterns. The visualizations offered a lucid depiction of data trends, equipping us to make informed choices for subsequent analysis or modeling.
