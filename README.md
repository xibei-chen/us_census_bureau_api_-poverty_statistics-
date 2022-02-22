# API Data Processing - US Census Bureau’s API (Poverty Statistics)

## Introduction
This is a project for my studies at CEU. The aim is to practice calling API and then process the data in the JSON response. I chose to use one of US Census Bureau’s APIs - Poverty Statistics: CPS & SAIPE (Time Series: various years). And I would also like to see if there is any significant difference among different races.

You can read more about how the script works and the relevant data visuals in the report html file.

## Approach
+ Create a function to get poverty data for a given time interval
+ Execute the function to get poverty data from 2008 to 2018

## Exploratory Data Analysis
1. Exploring the trend of percent of people in poverty in the US over time
From 2008 to 2018, the percent of people in poverty in the US is at its peak in 2010 and then decreases gradually during the following years, and in 2018 it is at its lowest around 11.8%.
2. Exploring difference among races in terms of poverty statistics
There is a significant difference among races in terms of the percent of people in poverty. For asian and white, the statistics are relatively low at around 11% and quite stable. However, the statistics for black and hispanic are around double the statistics for asian and white, which confirms my assumption. Besides, the trend of the statistics for black and hispanic are more similar to the whole population shown in the first chart, it might be the result of them having more people in poverty therefore having a bigger effect on the statistics for the whole population.

## Summary
To sum up, I had fun playing around with using the API of the US Census Bureau, creating a function in R to extract the data in JSON format, and eventually store the data in table format. The data visuals I created in the end also helped to confirm my assumption that there is a significant difference among different ethnic groups regarding wealth distribution in the US, which might be the result of meritocracy and institutional racism in the US.
