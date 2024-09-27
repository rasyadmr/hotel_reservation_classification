# Hotel Reservation Cancellation Predictor

## Project Overview

This machine learning project aims to predict whether a hotel reservation is likely to be cancelled or not. By analyzing various features of hotel bookings, we've developed a model that can assist hotels in managing their reservations more effectively.

## Table of Contents

1. [Installation](#installation)
2. [Data](#data)
3. [Model](#model)
4. [Evaluation](#evaluation)
5. [License](#license)

## Installation

To see this project, follow these steps to download the files:

```bash
git clone https://github.com/rasyadmr/hotel_reservation_classification.git
```

## Data

The model was trained on a dataset containing the following features:

- Booking_ID
- no_of_adults
- no_of_children
- no_of_weekend_nights
- no_of_week_nights
- type_of_meal_plan
- required_car_parking_space
- room_type_reserved
- lead_time
- arrival_year
- arrival_month
- arrival_date
- market_segment_type
- repeated_guest
- no_of_previous_cancellations
- no_of_previous_bookings_not_canceled
- avg_price_per_room
- no_of_special_requests
- booking_status

## Model

We used a Logistic Regression, Random Forest Classifier, and Decision Tree for this prediction task. The three models were used and compared to find the best model for this case. The result is that the random forest model is the best model.

## Evaluation

The models performance were evaluated using the following metrics:

### Logistic Regression

- Accuracy: 0.79
- Precision: 0.78
- Recall: 0.79
- F1-score: 0.78

### Random Forest

- Accuracy: 0.87
- Precision: 0.87
- Recall: 0.87
- F1-score: 0.87

### Decision Tree

- Accuracy: 0.84
- Precision: 0.84
- Recall: 0.84
- F1-score: 0.84

## License

This project is licensed under the MIT License
