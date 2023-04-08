# [H2O Olympics | H2O World India](https://h2o-olympics.h2o.ai/)

# Predicting the Air Quality Index of Indian Cities using Machine Learning

## Goal of the Competition

Air is what keeps humans alive. Monitoring it and understanding its quality is of immense importance to our well-being. In this hackathon, participants will have the opportunity to use their data analysis and machine learning skills to forecast the AQI for major Indian AQI stations for the upcoming 28 days. The dataset consists of the historical daily average of several air pollutants which directly affect the Air Quality Index.

Participants will be required to analyze this data and use it to build accurate models that can predict the AQI for each station.

## Dataset Description

The dataset consists of historical daily average pollutants, including SO, CO, PM2.5, and other important factors that affect the air quality index. Keep in mind that different AQI stations have different lengths of historical data. Your challenge in this competition is to forecast average AQI levels across different stations in India for the next 28 days.

## Files:

**train.csv - 2 years of historical data for 40 Indian AQI stations**

* ID_Date: Unique identifier of state, stationid and date
* StateCode: State where the AQI station is located
* StationId: AQI station ID
* Date: Date when the observations where recorded
* PM2.5: Average PM2.5 pollutant level
* PM10: Average PM10 pollutant level
* O3: Average O3 pollutant level
* CO: Average CO pollutant level
* SO2: Average SO2 pollutant level
* AQI: Average Air Quality Index - target variable

**sample_submission.csv - sample submission file to specify the submission format. This file will remain unchanged throughout the competition.**

* ID_Date: Unique identifier of state, stationid and date
* AQI: Average Air Quality Index


**Note:** We are not providing the test dataset as this is a forecasting competition and the pollutants level features are going to be unavailable during prediction time. You are required to predict AQI levels for all 40 unique AQI stations for the upcoming 28 days for a valid submission.
