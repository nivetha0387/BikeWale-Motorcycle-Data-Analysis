# BikeWale-Motorcycle-Data-Analysis
Web scraping, data cleaning and exploratory data analysis of BikeWale motorcycle data using Python.

# BikeWale Motorcycle Data Analysis & Insights

## 📌 Project Overview

This project focuses on collecting, cleaning, exploring and analyzing motorcycle data from BikeWale using Python.

The project follows an end-to-end data analysis workflow:

Web Scraping → Data Cleaning → EDA → Visualization → Correlation Analysis → Insights

## 🎯 Objectives

- Collect motorcycle data using web scraping
- Clean and prepare the dataset
- Analyze motorcycle specifications and pricing
- Understand relationships between numerical variables
- Compare fuel types
- Identify potential outliers
- Extract meaningful data-driven insights

## 🛠️ Technologies Used

- Python
- Requests
- BeautifulSoup
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🌐 Data Collection

The motorcycle data was collected from BikeWale using Python-based web scraping.

### Libraries Used

- Requests – Web requests
- BeautifulSoup – Web scraping
- Pandas – Data handling

## 🧹 Data Cleaning

The following data cleaning steps were performed:

- Converted numerical columns to appropriate data types
- Handled missing values based on fuel type
- Removed highly incomplete records
- Checked duplicate records
- Standardized numerical values
- Prepared the dataset for analysis

## 📊 Exploratory Data Analysis

### Univariate Analysis

Analyzed:

- Price Distribution
- Mileage Distribution
- Fuel Type Distribution
- Engine Capacity Distribution

### Bivariate Analysis

Analyzed:

- Price vs Engine Capacity
- Engine Capacity vs Kerb Weight
- Price vs Mileage
- Price vs Kerb Weight

### Multivariate Analysis

Used:

- Correlation Heatmap
- Pair Plot

## 🔍 Key Insights

- Engine Capacity and Kerb Weight show a strong positive relationship.
- Mileage shows a negative relationship with Engine Capacity.
- Mileage also shows a negative relationship with Kerb Weight.
- Price generally increases with Engine Capacity.
- Higher-priced bikes generally have lower mileage.
- Petrol bikes form the majority of the dataset.

## 📈 Correlation Highlights

- Engine Capacity ↔ Kerb Weight: 0.89
- Mileage ↔ Kerb Weight: -0.82
- Mileage ↔ Engine Capacity: -0.79
- Price ↔ Engine Capacity: 0.79

## 📁 Dataset

Final cleaned dataset:

- Rows: 59
- Columns: 12

## 📂 Project Files

- `BikeWale_CodingFile.ipynb` – Complete analysis notebook
- `BikeWale_Final_Cleaned.csv` – Cleaned dataset
- `BikeWale_PPT.pptx` – Project presentation

## 🚀 Future Improvements

- Add more motorcycle records
- Include brand and model information
- Add model year
- Add customer ratings
- Add sales volume
- Add location
- Build an interactive Power BI dashboard
- Explore machine learning applications

## 👩‍💻 Author

Nivetha S

Aspiring Data Analyst

Skills:
Python | SQL | Power BI | Excel | Data Analysis | Data Visualization
