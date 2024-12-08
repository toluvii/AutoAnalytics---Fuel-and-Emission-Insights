# AutoAnalytics---Fuel-and-Emission-Insights

Project Overview
This project analyzes and predicts fuel consumption and emissions across different vehicle types using machine learning techniques. It aims to identify trends, optimize fuel efficiency, and explore relationships between various vehicle attributes, offering valuable insights for automakers and policymakers.
________________________________________
Objectives
•	Analyze fuel efficiency and emission data.
•	Build predictive models for fuel consumption.
•	Uncover key factors affecting vehicle performance and emissions.
________________________________________
Dataset Overview
The dataset consists of 22,556 rows and 13 columns, including:
•	Vehicle Attributes: Make, Model, Vehicle Class, Engine Size, Cylinders, Transmission Type.
•	Performance Metrics: Fuel Consumption (city/highway/combined), Combined MPG, Emissions.
•	Fuel Type: Regular Gasoline, Premium Gasoline, Diesel, Ethanol, and Natural Gas.
________________________________________
Data Preprocessing
1.	Cleaning and Transformation:
o	Encoded categorical variables (e.g., Transmission, Fuel Type).
o	Addressed missing values and normalized numerical data.
2.	Feature Engineering:
o	One-hot encoding for fuel types.
o	Extracted descriptive labels for transmission types.
________________________________________
Exploratory Data Analysis
Key insights include:
•	Fuel Efficiency: Smaller engine sizes and fewer cylinders correlate with higher MPG.
•	Brand Performance: SMART and FIAT excel in fuel efficiency, while Bugatti ranks lowest.
•	Emission Trends: Higher fuel consumption leads to increased emissions.
________________________________________
Modeling and Evaluation
Three regression models were developed to predict fuel consumption:
1.	Random Forest Regressor
o	R² Score: 0.99998 (highest accuracy).
o	Cross-Validation: Consistent with minimal variance.
2.	Gradient Boosting Regressor
o	R² Score: 0.99993.
o	Slightly less consistent than Random Forest.
3.	Support Vector Regressor
o	R² Score: 0.84925.
o	Moderate accuracy with greater variability.
________________________________________
Key Findings
•	Transmission Impact: Continuously Variable Transmissions exhibit better fuel efficiency.
•	Vehicle Class: Compact and Subcompact vehicles outperform SUVs and Trucks in MPG.
•	Fuel Types: Ethanol and Natural Gas vehicles are less common but show promise in fuel efficiency.
________________________________________
🚀 Conclusion
This project demonstrates the power of data-driven analysis in understanding fuel efficiency and emissions. The Random Forest Regressor proved to be the most effective model, achieving near-perfect predictions. These insights can aid in designing environmentally friendly vehicles and optimizing automotive performance.

