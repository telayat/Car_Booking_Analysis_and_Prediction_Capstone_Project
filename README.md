# Car Booking Analysis and Prediction (Capstone Project)

![intro_image](https://github.com/telayat/Car_Booking_Analysis_and_Prediction_Capstone_Project/blob/main/Pics/carbooking.png)

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Dataset](#dataset)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
XGBoost library should be installed which can be done by running "pip install xgboost" command on terminal.
Other than this there should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

Car Booking Apps is a fast growing business in Egypt because it offers more reliable, secured and intelligent transportation options.
The winner in this area will be the one who employ data analytics to provide better customer service with minimal cost.

![problem_image](https://github.com/telayat/Car_Booking_Analysis_and_Prediction_Capstone_Project/blob/main/Pics/transportation_problem.jpg)

In this project I will answer some questions that shall help in providing better service and increase efficiency and revenue:
1. What are the top pick up locations per specific time?
2. What are the top pick up locations per specific times and favorite drop off list?
3. Predict fare amount?
4. Suggest best time to for a specific trip.

## Dataset<a name="dataset"></a>

Unfortunately, dataset is not available for the Egyptian market, so I will use a similar data from other markets to build and test the use case.
The data used were collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers authorized under the Taxicab & Livery Passenger Enhancement Programs (TPEP/LPEP).
I have used the Yellow Taxi trips data from year 2019 to avoid the impact of Covid-19 (over 40 million trips was used in the analysis).

The dataset can be found and downloaded from [here](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)


## File Descriptions <a name="files"></a>

I have added 1 notebook available here to showcase work related to the above questions.  it should be easy to navigate through the notebook from loading the dataset till answering the above questions one by one.
I have also added comments and markdown cells to make it easier to navigate and understand the file.  


## Results<a name="results"></a>

The main findings of the analysis and prediction can be found in the "Data Scientist Nano Degree (Capstone Project)" report [here](https://github.com/telayat/Car_Booking_Analysis_and_Prediction_Capstone_Project/blob/main/Data%20Scientist%20Nano%20Degree%20(Capstone%20Project).pdf) attached to this repo.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Thanks to NYC Taxi and Limousine Commission (TLC) and technology providers authorized under the Taxicab & Livery Passenger Enhancement Programs (TPEP/LPEP) for providing the dataset used in this analysis.
Licensing information and dataset can be found [here](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
