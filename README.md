# Titanic_analysis
It is a project on titanic datset.
# Titanic Dataset Exploratory Data Analysis (EDA)

This repository contains a project performing Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The main goal of this project is to clean the data, visualize key statistics, and identify patterns that may help in understanding the factors influencing survival rates.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis](#analysis)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Titanic dataset is one of the most popular datasets in data science and machine learning. It provides information on the passengers of the Titanic, which sank in 1912. The dataset includes features such as age, sex, ticket class, and whether the passenger survived or not.

## Dataset
The dataset used in this project is the Titanic dataset from Kaggle. It contains the following features:
- **Survived:** Survival (0 = No, 1 = Yes)
- **Pclass:** Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Sex:** Sex
- **Age:** Age in years
- **SibSp:** Number of siblings/spouses aboard the Titanic
- **Parch:** Number of parents/children aboard the Titanic
- **Fare:** Passenger fare
- **Embarked:** Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Project Structure
titanic-eda/
├── data/
│ └── titanic.csv
├── notebooks/
│ └── titanic_eda.ipynb
├── src/
│ └── eda.py
├── README.md
└── requirements.txt

- `data/`: Directory containing the dataset.
- `notebooks/`: Directory containing Jupyter Notebooks with the analysis.
- `src/`: Directory containing the Python script for the EDA.
- `README.md`: This file.
- `requirements.txt`: List of Python libraries required for this project.

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/titanic-eda.git
   cd titanic-eda

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt
## Usage

### Run the Jupyter Notebook:
#### jupyter notebook notebooks/titanic_eda.ipynb
### Run the Python script:
#### python src/eda.py

### Analysis

#### The analysis includes:

###### Data Cleaning: Handling missing values, converting categorical variables, and dropping unnecessary columns.
###### Univariate Analysis: Distribution of age, survival count.
###### Bivariate Analysis: Survival rate by sex, age distribution by survival status.
###### Multivariate Analysis: Pair plots and heatmap of correlations.

#### Key Findings:
##### The survival rate is higher for females compared to males.
##### Passengers in higher classes (1st class) had higher survival rates.
##### There is a noticeable difference in age distribution between survivors and non-survivors.

#### Contributing
##### Contributions are welcome! Please open an issue or submit a pull request for any changes or enhancements.
