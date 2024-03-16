# British Airways: Data Science Job Simulation

**Overview**

This repository contains the code and findings for the "British Airways: Data Science Job Simulation" project. The project aims to simulate various data science tasks and analyses within the context of British Airways, a leading airline company.

**Findings**

### Exploratory Data Analysis (EDA)

- The dataset consists of 50,000 records and includes features such as `num_passengers`, `sales_channel`, `trip_type`, `purchase_lead`, `length_of_stay`, `flight_hour`, `flight_day`, `route`, `booking_origin`, `wants_extra_baggage`, `wants_preferred_seat`, `wants_in_flight_meals`, `flight_duration`, and `booking_complete`.
- After converting the `flight_day` feature into numerical form, the dataset was further explored to understand the statistical properties of each column.

### Predictive Modeling

- A RandomForestClassifier was trained using the features to predict the target variable `booking_complete`, which indicates whether a customer completed a booking or not.
- The model achieved an accuracy of 85% on the test data, with precision, recall, and F1-score of 0.87, 0.98, and 0.92 respectively for class 0, and 0.52, 0.15, and 0.23 respectively for class 1.

### Feature Importance

- Feature importance analysis revealed that the top three features contributing to the prediction of booking completion were `purchase_lead`, `flight_hour`, and `length_of_stay`.

**Conclusion**

The analysis provides valuable insights into customer booking behavior and factors influencing booking completion. These findings can inform decision-making processes within British Airways and support efforts to optimize operations and enhance customer satisfaction.

**Repository Structure**

- `data`: Directory containing the dataset used for analysis.
- `notebooks`: Jupyter notebooks containing code for data exploration, modeling, and analysis.
- `README.md`: Overview of the project and key findings.
- `LICENSE`: MIT License for the repository.

**Dependencies**

The project requires the following Python libraries:

- pandas
- scikit-learn
- matplotlib

**Usage**

1. Clone the repository to your local machine.
2. Navigate to the `notebooks` directory.
3. Open the Jupyter notebooks to view the code and analysis.

**License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
