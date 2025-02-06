# Exploratory-Data-Analysis-in-Python
To performing Exploratory Data Analysis (EDA) using Python focusing on the use of NumPy and Pandas for data manipulation and analysis.

## Overview
This project analyzes the population and murder rates of U.S. states using Python. The dataset includes information about each state's population and corresponding murder rate, which is visualized using bar charts.

## Dataset
The dataset contains the following columns:
- `State`: Name of the U.S. state
- `Population`: Total population of the state
- `Murder.Rate`: Murder rate per 100,000 people

## Installation
To run this project, ensure you have Python installed along with the following dependencies:
```bash
pip install pandas seaborn matplotlib
```

## Usage
1. Load the dataset using pandas.
2. Convert data types if necessary (e.g., `Murder.Rate` to float).
3. Generate bar plots for:
   - Population by State
   - Murder Rate by State
4. Customize plots for better readability.

Run the script using:
```bash
python analysis.py
```

## Visualizations
The project includes the following visualizations:
- **Population Bar Chart**: Displays state populations sorted by murder rate.
- **Murder Rate Bar Chart**: Shows murder rates across states.

## Notes
- Ensure `Murder.Rate` is correctly converted to `float` to avoid plotting issues.
- Adjust figure size and label rotation for improved readability.
