# NYC TLC Trip Record Analysis

## Project Overview
This project analyzes New York City Taxi and Limousine Commission (TLC) trip records to understand passenger travel behavior and identify factors that influence the choice between Street-hail and Dispatch services.

The analysis focuses on trip characteristics such as distance, pickup and dropoff locations, travel time, fare amount, payment methods, and passenger count.

---

## Business Problem

Transportation companies need to better understand passenger behavior to:

- Improve service quality
- Optimize taxi fleet allocation
- Reduce operational costs
- Enhance customer satisfaction
- Support data-driven decision making

Key question:

> What factors influence passengers to choose Street-hail versus Dispatch taxi services?

---

## Dataset

Source: NYC Taxi and Limousine Commission (TLC)

The dataset contains information such as:

- Vendor ID
- Pickup and Dropoff Datetime
- Pickup and Dropoff Locations
- Passenger Count
- Trip Distance
- Fare Amount
- Tip Amount
- Total Amount
- Payment Type
- Trip Type

---

## Data Cleaning

The following data preparation steps were performed:

- Converted datetime columns to proper datetime format
- Removed columns with 100% missing values
- Handled missing values
- Removed incomplete records
- Corrected invalid negative values
- Recalculated total fare amounts
- Created trip status categories

---

## Exploratory Data Analysis

The analysis explored:

### Vendor Analysis
- Comparison between Creative Mobile Technologies and VeriFone Inc

### Location Analysis
- Most popular pickup zones
- Most popular dropoff zones
- Location differences between Street-hail and Dispatch

### Time Analysis
- Passenger behavior based on pickup hours
- Peak demand periods

### Distance Analysis
- Relationship between trip distance and trip type

### Fare Analysis
- Fare amount
- Tip amount
- Payment methods
- Rate code categories

### Passenger Analysis
- Passenger count distribution
- Relationship between passenger count and trip type

---

## Key Findings

- Street-hail trips dominate overall trip volume.
- Short-distance trips are more likely to use Street-hail services.
- Dispatch trips are generally associated with longer distances.
- Credit card payments are the most commonly used payment method.
- Passenger behavior varies significantly by location and pickup time.
- Passenger count influences the likelihood of choosing Dispatch services.

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-Learn

---

## Project Structure

```
├── CAPSTONE PROJECT MODUL 2.ipynb
├── README.md
```

---

## Author

**Ulfah Rosdiana**

- Accounting Graduate
- Aspiring Data Analyst
- Interested in Data Analytics, Machine Learning, and Business Intelligence

LinkedIn:
https://www.linkedin.com/in/ulfah-rosdiana-86165a255
