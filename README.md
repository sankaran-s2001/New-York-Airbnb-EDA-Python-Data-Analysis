# 🏠 New York Airbnb EDA - Python Data Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=for-the-badge&logo=seaborn&logoColor=white) ![EDA](https://img.shields.io/badge/EDA-FF9800?style=for-the-badge&logo=googleanalytics&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white) ![CSV](https://img.shields.io/badge/CSV-1572B6?style=for-the-badge&logo=files&logoColor=white)

Exploratory data analysis of New York's Airbnb listings using Python, analyzing room types, pricing, availability, and geographic distribution across NYC boroughs.

## 🎯 What This Project Shows

This analysis explores Airbnb rental patterns in New York City to understand:

- Room type preferences and distribution
- Pricing patterns across different areas
- Seasonal availability trends
- Geographic concentration of listings
- Correlations between different variables


## 📊 Dataset Overview

- **Total Listings**: 20,758 Airbnb properties
- **Boroughs**: Brooklyn, Manhattan, Queens, Bronx, Staten Island
- **Room Types**: Entire home/apt, Private room, Hotel room, Shared room
- **Average Price**: ~\$188 per night
- **Minimum Stay**: Most hosts require 30+ nights


## 📈 Key Analysis Results

### 1. **Room Type Distribution**

- **Entire home/apt**: 11,551 listings (55.7%) - Most popular
- **Private room**: 8,802 listings (42.4%) - Second choice
- **Shared room**: 293 listings (1.4%) - Minimal
- **Hotel room**: 112 listings (0.5%) - Rare


### 2. **Geographic Distribution**

- **Manhattan**: 8,038 listings (38.7%) - Highest concentration
- **Brooklyn**: 7,719 listings (37.2%) - Close second
- **Queens**: 3,761 listings (18.1%) - Moderate presence
- **Bronx**: 949 listings (4.6%) - Limited options
- **Staten Island**: 291 listings (1.4%) - Lowest


### 3. **Room Types by Borough**

- **Brooklyn**: Strong in private rooms (3,463) and entire homes (4,130)
- **Manhattan**: Dominated by entire homes (5,239) with private rooms (2,571)
- **Queens**: Balanced mix with private rooms (2,093) and entire homes (1,506)
- **Bronx \& Staten Island**: Smaller markets with mixed offerings


### 4. **Pricing Analysis**

- **Hotel rooms**: Highest average price (~\$350)
- **Entire home/apt**: Second highest (~\$200)
- **Private room**: Moderate pricing (~\$100)
- **Shared room**: Lowest cost (~\$75)


### 5. **Availability Patterns**

- **Peak availability**: 350+ days (5,392 listings) - Year-round rentals
- **Low availability**: 0-50 days (3,774 listings) - Occasional rentals
- **Medium availability**: 100-300 days - Part-time rentals
- **Seasonal variations**: Clear patterns throughout the year


### 6. **Correlation Insights**

- Strong correlations between price and room type
- Geographic location influences pricing
- Availability affects booking patterns
- Number of reviews indicates popularity


## 🔍 Key Business Insights

### Market Dominance

- Entire apartments dominate the market (55.7%)
- Manhattan and Brooklyn control 75.9% of all listings
- Private rooms offer budget-friendly alternatives


### Pricing Strategy

- Hotel rooms command premium prices
- Location significantly impacts pricing
- Shared rooms provide cheapest options


### Host Behavior

- Most hosts prefer long-term stays (30+ nights minimum)
- Year-round availability indicates professional hosting
- Review patterns show guest satisfaction levels


### Geographic Patterns

- Manhattan focuses on entire apartments for tourists
- Brooklyn offers more private room options
- Outer boroughs provide affordable alternatives


## 🛠️ Python Libraries Used

- **pandas**: Data manipulation and analysis
- **matplotlib**: Data visualization
- **seaborn**: Statistical plotting
- **numpy**: Numerical computations
- **plotly**: Interactive visualizations


## 📁 Project Files

```
📦 nyc-airbnb-eda/
├── 📄 README.md                         (This file)
├── 📓 EDA_Airbnb.ipynb                  (Jupyter notebook)
├── 📋 datasets.csv                      (Raw Airbnb data)
├── 📋 Newyork_Airbnb_Clean_dataset.csv  (Cleaned data)
├── 📊 Correlation_Matrix_Heatmap.png    (Correlation analysis)
├── 📊 Distribution_of_room_types.png    (Room type chart)
├── 📊 Number_of_listings_by_town.png    (Geographic distribution)
├── 📊 Plot_availability_throughout_year.png (Seasonal trends)
├── 📊 Price_by_Room_Type.png           (Pricing analysis)
└── 📊 Room_types_in_each_town.png      (Borough breakdown)
```


## 🚀 How to Run This Analysis

### Prerequisites

- Python 3.7+
- Jupyter Notebook
- Required libraries: pandas, matplotlib, seaborn, numpy


### Steps

1. **Clone the repository**
2. **Install required packages**: `pip install pandas matplotlib seaborn numpy`
3. **Open Jupyter Notebook**: `jupyter notebook EDA_Airbnb.ipynb`
4. **Run all cells** to see the complete analysis

## 💡 Data Science Skills Demonstrated

- ✅ **Data Cleaning**: Handling missing values and data preparation
- ✅ **Exploratory Data Analysis**: Comprehensive data exploration
- ✅ **Data Visualization**: Multiple chart types and insights
- ✅ **Statistical Analysis**: Correlation analysis and patterns
- ✅ **Business Intelligence**: Market insights and recommendations
- ✅ **Python Proficiency**: pandas, matplotlib, seaborn usage


## 🔮 Potential Applications

- **Investment Decisions**: Identify profitable areas for Airbnb investment
- **Pricing Strategy**: Set competitive rates based on location and room type
- **Market Research**: Understand NYC short-term rental market
- **Tourism Planning**: Help travelers find suitable accommodations
- **Policy Analysis**: Support city planning and regulation decisions


## 📝 Key Findings Summary

1. **Entire apartments dominate** NYC Airbnb market
2. **Manhattan and Brooklyn** are the primary markets
3. **Hotel rooms are premium priced** but rare
4. **Availability patterns** show professional vs casual hosting
5. **Geographic location** significantly impacts pricing
6. **Private rooms** offer budget-friendly options
7. **Year-round availability** indicates established rental business

***

**Created by**: [sankaran-s2001](https://github.com/sankaran-s2001)
**Tools Used**: Python, Jupyter Notebook, pandas, matplotlib, seaborn
**Project Type**: Exploratory Data Analysis
**Domain**: Real Estate \& Tourism Analytics

## ✉️ Contact

**Sankaran S**  
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sankaran-s2001) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sankaran-s21/) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sankaran121101@gmail.com)

*Complete EDA of 20,000+ NYC Airbnb listings with comprehensive insights and visualizations*
