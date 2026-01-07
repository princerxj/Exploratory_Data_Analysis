# Exploratory Data Analysis

This is a learning and revision repository for practicing EDA techniques.

## Contents

### 1.0-WinequalityEDA.ipynb
Exploratory Data Analysis on Red Wine Quality dataset.

**Dataset Information:**
- Portuguese "Vinho Verde" wine dataset (red variants)
- Contains physicochemical and sensory variables
- Can be used for classification or regression tasks

**Features (Input variables):**
1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol

**Target variable:**
- quality (score between 0 and 10)

**Libraries used:**
- pandas
- matplotlib
- seaborn

### 2.0-FlightPricePredictionEDA.ipynb
EDA and Feature Engineering for Flight Price Prediction.

**Features:**
1. **Airline:** Name of the airline company (6 different airlines)
2. **Flight:** Flight code information
3. **Source City:** City from which the flight takes off (6 unique cities)
4. **Departure Time:** Derived categorical feature with 6 time labels
5. **Stops:** Number of stops between source and destination (3 distinct values)
6. **Arrival Time:** Derived categorical feature with 6 time labels
7. **Destination City:** City where the flight lands (6 unique cities)
8. **Class:** Seat class information (Business and Economy)
9. **Duration:** Total travel time between cities in hours
10. **Days Left:** Derived feature (trip date - booking date)
11. **Price:** Target variable (ticket price)

**Libraries used:**
- pandas
- numpy
- seaborn
- matplotlib

## Dataset Files
- `winequality-red.csv` - Red wine quality dataset
- 'flight_price.xlsx' - Flight Price Dataset
