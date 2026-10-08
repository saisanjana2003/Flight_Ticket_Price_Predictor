# Flight Ticket Price Predictor using Machine Learning

A machine learning-based web application that predicts flight ticket prices based on flight-related information provided by the user.

## Project Overview

Flight ticket prices vary depending on factors such as airline, source, destination, journey date, duration, and number of stops.

This project uses machine learning to analyze flight-related data and predict ticket prices. The prediction system is integrated into a web application, allowing users to enter flight details and obtain a predicted ticket price.

## Features

- Flight ticket price prediction using machine learning
- User-friendly web interface
- Flight price dataset for model development
- Django-based web application
- Database integration for user signup
- Prediction results displayed through the application
- Application and output screenshots

## Technologies Used

- Python
- Machine Learning
- Django
- HTML
- CSS
- JavaScript
- SQL
- Pandas
- NumPy
- Scikit-learn

## Project Structure

```text
FlightPrice/
│
├── Dataset/
├── Flight/
├── flightprice/
├── Screens/
├── DB.txt
├── Manage
├── Requirements
├── Run
└── README.md
Dataset

The project contains flight-related Excel datasets used for developing and testing the prediction system:

* data train.xlsx
* flight price.xlsx

How It Works

1. Flight-related data is collected from the available datasets.
2. The data is processed and prepared for machine learning.
3. A machine learning model is developed using the flight-related features.
4. The model is integrated with the Django web application.
5. Users enter their flight details through the web interface.
6. The application processes the input data.
7. The predicted flight ticket price is displayed to the user.

Database

The project includes DB.txt, which contains SQL commands for creating the FlightPrice database and the signup table used by the application.

Screenshots

The Screens folder contains screenshots of the application interface and prediction outputs.

Installation and Usage

1. Clone the repository

git clone https://github.com/saisanjana2003/Flight_Ticket_Price_Predictor.git

2. Navigate to the project folder

cd Flight_Ticket_Price_Predictor

3. Install the required dependencies

pip install -r requirements.txt

4. Run the Django application

python manage.py runserver

Open the local server address provided by Django in your browser.
Future Enhancements

* Improve prediction accuracy with additional flight data
* Experiment with different machine learning algorithms
* Deploy the application online
* Add more data visualization features
* Improve the user interface and user experience

Author

Saisanjana

GitHub: https://github.com/saisanjana2003