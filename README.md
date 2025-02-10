# machine-learning-project
Road Accident Predicting System

Project Overview

The Road Accident Predicting System is a data-driven project aimed at analyzing and forecasting road accident probabilities based on historical accident data from Great Britain in 2012. The project utilizes machine learning techniques to identify high-risk areas and provide insights for traffic management authorities. The primary objective is to use predictive modeling to assist in proactive decision-making regarding road safety measures.

Objective
	•	To analyze accident-related factors and identify high-risk areas using data science techniques.
	•	To build a predictive model that estimates accident likelihood based on factors such as speed limit, latitude, longitude, and accident severity.
	•	To develop a system that enables traffic authorities to allocate resources efficiently for accident prevention.

Dataset Description

The dataset used in this project contains 145,571 records with 34 attributes related to reported accidents. The data includes crucial information such as:
	•	Location details (latitude, longitude, and region codes).
	•	Speed limits and road conditions.
	•	Severity levels of accidents.

During preprocessing, missing values were analyzed, and the dataset was refined by removing unnecessary records and handling null values. Outlier detection was performed using Z-score and interquartile range (IQR) methods to improve data quality. The final dataset after preprocessing contains 143,178 records and 34 columns.

Exploratory Data Analysis
	•	Analysis was conducted on accident severity concerning speed limits, location, and other relevant factors.
	•	Data visualization techniques, including scatter plots and heatmaps, were used to examine accident trends.
	•	The impact of vehicle speed on accident severity was assessed to develop predictive insights.

Machine Learning Model Development

Multiple machine learning algorithms were implemented and evaluated for accident prediction. The models used in the study include:
	1.	Logistic Regression
	2.	Random Forest (Best performing model)
	3.	Decision Tree
	4.	K-Nearest Neighbors (KNN)
	5.	Gaussian Naïve Bayes


Key Features and Insights
	•	Predictive Modeling: The system forecasts accident probabilities based on speed limits, location coordinates, and historical accident data.
	•	Data Cleaning and Preprocessing: The dataset was processed to remove missing values and outliers to improve model accuracy.
	•	Comparative Model Analysis: Various classification algorithms were tested, with the Random Forest model achieving the highest accuracy.
	•	Visualization and Insights: Spatial analysis of accidents was conducted to identify trends and high-risk zones.

Future Enhancements
	1.	Integration of Weather Data
	•	Future improvements will include weather-related parameters such as precipitation, visibility, and road conditions. This will allow for a more comprehensive prediction model.
	2.	Real-Time Accident Prediction
	•	The project can be enhanced by integrating real-time traffic and weather data using Internet of Things (IoT) devices and streaming analytics.
	3.	Deployment as a Web-Based Tool
	•	The predictive system can be deployed as a web application for use by law enforcement and transportation authorities to assist in real-time decision-making.

Technologies and Tools Used
	•	Programming Language: Python
	•	Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
	•	Machine Learning Techniques: Logistic Regression, Random Forest, Decision Tree, K-Nearest Neighbors, Gaussian Naïve Bayes
	•	Visualization Tools: Matplotlib, Seaborn
	•	Data Processing Techniques: Outlier detection, Feature engineering, Model evaluation



