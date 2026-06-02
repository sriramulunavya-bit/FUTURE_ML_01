# Sales Forecasting Using Linear Regression

## Project Overview

This project predicts future sales using Machine Learning techniques. Historical sales data is analyzed and a Linear Regression model is trained to forecast upcoming sales trends.

The project uses sales records containing order dates and total revenue values. After preprocessing the data, a regression model is built to predict future sales for the next 30 days.

## Features

* Load and preprocess sales data
* Convert date information into a time-series format
* Train a Linear Regression model
* Forecast future sales
* Visualize actual and predicted sales trends
* Generate sales forecasting graphs

## Dataset

The dataset should contain at least the following columns:

| Column Name   | Description                    |
| ------------- | ------------------------------ |
| Order Date    | Date of the sales transaction  |
| Total Revenue | Revenue generated on that date |

Example:

| Order Date | Total Revenue |
| ---------- | ------------- |
| 01/01/2024 | 5000          |
| 01/02/2024 | 6200          |
| 01/03/2024 | 5800          |

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn

## Machine Learning Algorithm

### Linear Regression

Linear Regression is used to identify the relationship between time and sales values. The model learns historical sales patterns and predicts future sales.

## Installation

1. Clone the repository:

```bash
git clone <repository-url>
cd sales-forecasting
```

2. Install required packages:

```bash
pip install -r requirements.txt
```

## Usage

1. Place the dataset file (`sales.csv`) in the project directory.

2. Run the notebook:

```bash
jupyter notebook sales_forecasting.ipynb
```

3. Execute all cells.

## Output

The project generates:

* Future sales predictions for the next 30 days
* Sales trend visualization
* Forecasted sales graph

## Project Structure

```text
sales-forecasting/
│
├── sales_forecasting.ipynb
├── sales.csv
├── README.md
├── requirements.txt
└── images/
    └── sales_trend.png
```

## Future Enhancements

* Support multiple forecasting algorithms
* Improve forecasting accuracy using advanced ML models
* Interactive dashboard using Streamlit
* Automated model evaluation metrics

## Author

SRIRAMULU NAVYA SREE
