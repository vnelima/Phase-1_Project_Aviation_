# Aviation Risk Assessment and Aircraft Risk Prediction.

## Background	
The company is expanding in to new industries to diversify its portfolio. Specifically interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. I have been charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. I have translated my findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.
•	Some of the risks I have identified include the following:
* Human error eg Pilot error or Crew fatigue
* Mechanical failures eg Engine malfunction or poor maintenance due to factors such as Wear and Tear
* Environment risks eg weather conditions and geographical hazards
* Regulatory and Compliance Risks such as failure to adhere to safety regulations
* To reduce the potential risks and financial impact, we need to do the following
* Improve safety standards and technology on the aircraft make and model
* Ensure operationally, regular and scheduled maintenance of the aircraft
* Focus on human factors such as pilot and crew training

## Problem Statement:
We would like to address the following:
o	which aircraft are the safest and pose the lowest risk for the company?
o	What are the key risks in terms of purchasing aircraft with poor safety records, geographical or environmental risks that affect operations and lack of understanding of amateur-built aircrafts
o	Problems such as potential for operational inefficiencies due to unrecognized risks.

## Objectives:
The Overall objective is to identify the lowest-risk aircraft models to guide the company’s purchase decisions.
The Specific Objectives that feed into the overall objective are
1.	To determine which aircraft models/makes have the lowest risk for the company.
2.	To identify the aircraft that are most likely to be involved in accidents.
3.	To analyze high-risk locations/environments to guide operational decisions.
4.	To evaluate whether to invest in amateur-built aircraft.
5.	To analyze factors contributing to aviation risks (weather, make/model, location).
6.	To assess the purpose of the flight (commercial, private, training) and its impact on risk

## EDA
The data we were given were pulled from https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses.

## Description of data

Importing Libraries
numpy is a python library that helps us work with large arrays
import numpy as np
pandas is used for manipulating spreadsheets
import pandas as pd
matplotlib enbles us to plot a line plot with x and y axis
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns

## Loading data
### Reading dataset from CSV file and creating the dataset
df = pd.read_csv("AviationData.csv", encoding='latin-1')

## Cleaning data
Cleaned_aviation_data.csv

## Visualizations
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)

# Observations and Findings:
* Accident Frequency:
* Some aircraft models have higher accident frequencies, making them riskier investments.

* Environmental Risk:
* Incidents are more common in certain weather conditions (e.g., "UNK"/unreported weather).

* Amateur-Built Aircraft:
* amateur-built aircraft pose a higher risk compared to standard commercial/private aircraft and we probably need to do more tests on the amateur flights before investing in them

*Purpose of Flight:
* The risk based on the purpose of the flight (commercial operations, training flights, etc.) is lower as compared to personal flights. This could be due to several factors such as the number of people that use the personal flights are more than 


## Risk Assessment:
* ranking of aircraft based on calculated accident risk is that Cessna comes top with highest frequency of accidents, followed by Piper and then Beech.
* ranking of models frequently involved in accidents is 152, 172, 172N in that order of top three
* Higher severity models DC-8-62, A320-216, MD-83 are more likely to result in costly and dangerous accidents.
* Amateur built aircrafts have higher accident frequency
* high-risk weather conditions is actually when pilot has good visibility as we have more accidents.

## Recommendations:
* Aircraft to Consider:
* Based on the analysis, I would recommend Boeing models as the ratio of accident rates to total uninjured is reasonable
* Amateur-Built Aircraft:
* I would not recommend to invest in amateur-built aircrafts based on risk analysis as it requires more tests 
* Operational Insights:
* Even if the weather condition has good visibility I would still recommend instruments to be used to assist the pilot so no mistakes are done to avoid accidents










