# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)  Project 1: Driving Licenses, Traffic Accidents and Casualties Analysis


---
## Problem Statment

Investigate whether there is a relationship between the number of licenses and traffic accidents, and check whether accidents increase or decrease in general in the Kingdom of Saudi Arabia.
---
### Executive Summary

Makkah Al-Mukarramah contains the highest rate of accidents, deaths and injuries in the Kingdom of Saudi Arabia, while the northern region of the Kingdom contains the lowest number of accidents, but the positive side is that these accidents decrease every year from the previous year, unfortunately I do not have years older than 2016 to measure if the positive progress The number of accidents decreased after the implementation of the Saher system.

---

### Datasets and Appendix

For this project, I have three provided datasets:

- [Traffic Accidents and Casualties by Region 2016-2017](https://git.generalassemb.ly/DSI-MISK-VIII/Project-1/blob/master/data/saudi-arabia-traffic-accidents-2008.csv)
- [Traffic Accidents and Casualties by Region 2016-2019](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/information/?disjunctive.region&disjunctive.indicator)
- [Driving Licenses Issued By Administrative Area](https://git.generalassemb.ly/DSI-MISK-VIII/Project-1/blob/master/data/saudi-arabia-driving-licenses-2004-2008.csv)
- [Article](https://najwasaeed.blogspot.com/2021/01/the-most-dangerous-city-for-drivers-in.html)



---
## Data dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|unnamed_col1|int64|Traffic_Accidents|Unknown number|
|unnamed_col2|int64|Traffic_Accidents|Unknown number|
|year|int64|Traffic_Accidents|The year they collected the data in|
|region|str64|Traffic_Accidents|The city from which the data are collected|
|state|str64|Traffic_Accidents|Casualties or Accidents/Dead or Injured|
|coordinates|float64|Traffic_Accidents|Used to determine any place on the earth using latitude(x) and longitude(y)|
|x_coordinate|float64|Traffic_Accidents|latitude(x)|
|y_coordinate|float64|Traffic_Accidents|and longitude(y)|




|Feature|Type|Dataset|Description|
|---|---|---|---|
|unnamed_col1|int64|Driving_Licenses|Unknown number|
|year|int64|Driving_Licenses|The year they collected the data in|
|administritive_area|str64|Driving_Licenses|The city from which the data are collected|
|driving_licenses_number|str64|Driving_Licenses|Number of license holders|
|coordinates|float64|Driving_Licenses|Used to determine any place on the earth using latitude(x) and longitude(y)|
|x_coordinate|float64|Driving_Licenses|latitude(x)|
|y_coordinate|float64|Driving_Licenses|and longitude(y)|



---


## Conclusions and Recommendations
I advise to focus on the Makkah region, but to get a clearer result, we must obtain more information and characteristics such as the age, health and mental state of the driver, and whether the cause of the accident was a human error or for another reason such as the air suit for the weather or a malfunction in the vehicle ... etc.
---
