Real Estate Price Anomaly Detection with Machine Learning

This project utilizes machine learning models to detect anomalies in property prices based on various features, such as location, property type, area size, and price. The models used for anomaly detection are Random Forest and Isolation Forest.

Key Features:
	•	Anomaly Detection: The system identifies whether a property price deviates significantly from expected ranges based on historical data.
	•	ML Models: The project integrates Random Forest and Isolation Forest models for anomaly detection.
	•	Property Validation: The API validates properties based on location, property type, area size, and price.
	•	Scalable and Efficient: The project uses a simple Flask API to expose the anomaly detection functionality, which can be easily integrated with any front-end application.

Technologies Used:
	•	Flask: A lightweight web framework for Python to create the API.
	•	scikit-learn: Used for building and using the machine learning models (Random Forest, Isolation Forest).
	•	Joblib: Used for saving and loading trained models.
	•	Numpy: For handling numerical operations and transforming input features.

How It Works:
	1.	The user sends a POST request to the /validateProperty endpoint with property data.
	2.	The data is processed, including encoding categorical variables like location and property type.
	3.	The data is then scaled and passed to the trained models for anomaly detection.
	4.	The system returns whether the property price is valid or an anomaly.

Installation:

To use the API, clone this repository, install the required dependencies, and ensure you have the .pkl model files available
