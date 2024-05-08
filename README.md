# FlexiRelief: Pain Management Application
The FlexiRelief Application is designed to assist users in predicting diseases by inputting their symptoms. Utilizing machine learning algorithms, particularly Decision Tree Classifier and Support Vector Machine (SVM), it predicts diseases based on symptom patterns and offers information on their descriptions and precautionary measures. It is a pain management application that helps users identify potential diseases based on symptoms they are experiencing. 

## Features

- **User Input**: Users can input their name, symptoms they are experiencing, and the duration of their symptoms.
- **Symptom Selection**: Users can select specific symptoms from a list provided by the application.
- **Disease Prediction**: The application predicts diseases based on the entered symptoms and displays the predicted disease along with its description and precautionary measures.
- **Easy-to-Use Interface**: The application provides a user-friendly interface for easy interaction.

## Installation and Usage
1. Clone the repository:
```
git clone https://github.com/nanditha-kathiravan/FlexiRelief-Pain-Management-Application
```
2. Install the required dependencies:
```
pip install -r requirements.txt
```
3. Run the Streamlit application:
```
streamlit run main.py
```
4. Access the application in your web browser by navigating to the provided local URL.

## Data Sources
- **Training Data**: The application uses training data stored in CSV files (Training.csv, Testing.csv) to train the machine learning model for disease prediction.
- **Symptom Descriptions**: Symptom descriptions are sourced from the Indicator_Description.csv file.
- **Symptom Severity**: Symptom severity data is sourced from the Indicator_severity.csv file.
- **Precautionary Measures**: Precautionary measures for diseases are sourced from the Indicator_precaution.csv file.

## Tech Stack
- **Python**: The backend of the application is developed using Python programming language.
- **Streamlit**: The user interface is built using Streamlit, a Python library for creating web applications.
- **Machine Learning**: Machine learning techniques, including Decision Tree Classifier and Support Vector Classifier (SVC), are used for disease prediction.
- **GitHub Actions**: GitHub Actions is used for continuous integration to automate the build and deployment process.
