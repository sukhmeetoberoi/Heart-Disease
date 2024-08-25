# Heart Disease Prediction

This project is a user-friendly GUI application that predicts the likelihood of heart disease based on various health-related inputs provided by the user. The prediction model is powered by Logistic Regression, and the application is built using Python's `tkinter` for the GUI and `scikit-learn` for machine learning.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Details](#model-details)
- [Performance](#performance)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

The Heart Disease Prediction application provides a simple interface for users to enter their health metrics and receive a prediction regarding their risk of heart disease. The model is trained on a well-known heart disease dataset, and the predictions are based on key health indicators such as age, cholesterol levels, blood pressure, and more.

## Features

- **Interactive User Interface:** Simple and intuitive GUI built with `tkinter` for easy user interaction.
- **Health Metrics Input:** Collects key health-related inputs like age, BMI, cholesterol levels, smoking habits, and more.
- **Real-Time Prediction:** Provides instant prediction on heart disease risk based on user inputs.
- **Model Accuracy Display:** Shows the accuracy of the model on the training dataset after each prediction.

## Installation

### Prerequisites

Before running the application, ensure you have the following installed on your system:

- Python 3.x
- pip (Python package installer)

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/sukhmeetoberoi/Heart-Disease
   cd Heart-Disease
Install dependencies: Install the required Python packages using the following command:

bash
Copy code
pip install -r requirements.txt
Run the application: Execute the following command to start the application:

bash
Copy code
python app.py
Usage
Launch the Application: Run app.py to open the GUI.
Input Health Data: Enter the required health metrics in the corresponding fields (e.g., age, gender, cholesterol levels, etc.).
Make a Prediction: Click the "Predict" button to receive the prediction.
View Results: The application will display whether you are at risk of heart disease along with the model's accuracy score.

Dataset
The model is trained on a heart disease dataset containing various health-related features. These features include:

Gender (0 for female, 1 for male)
Age
Education level (0 for no education, 1 for education)
Smoking status (0 for non-smoker, 1 for smoker)
Number of cigarettes per day
Use of blood pressure medication (0 for no, 1 for yes)
History of stroke (0 for no, 1 for yes)
Presence of hypertension (0 for no, 1 for yes)
Diabetes status (0 for no, 1 for yes)
Total cholesterol level
Systolic blood pressure
Diastolic blood pressure
Body Mass Index (BMI)
Resting heart rate
Average glucose level

The dataset is preprocessed to handle missing values and standardized before being used for model training.

Model Details
Algorithm: Logistic Regression


Data Preprocessing:
Missing values are handled using SimpleImputer with the mean strategy.
Features are standardized using StandardScaler to improve model performance.
The Logistic Regression model is chosen for its efficiency and effectiveness in binary classification tasks like predicting heart disease.

Performance
Training Accuracy: The application provides the accuracy score of the model on the training dataset after each prediction.
Prediction Accuracy: The model’s performance can be evaluated by its accuracy score, which is displayed in the GUI.


Screenshots

![Screenshot 2024-08-26 013948](https://github.com/user-attachments/assets/54393bcb-9c08-4bba-960d-da6adb44b590)
![Screenshot 2024-08-26 014008](https://github.com/user-attachments/assets/ce15d666-1185-436f-89b6-7c4f9c1cb0ce)
![Screenshot 2024-08-26 014002](https://github.com/user-attachments/assets/22515ce8-086f-4abf-8c5b-2471c7a0bbca)



Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Open a Pull Request.


Contact
For any inquiries or feedback, please contact:
Name: Sukhmeet Singh Oberoi
Email: sukhmeetoberoi@gmail.com
Feel free to reach out if you have any questions or suggestions!
