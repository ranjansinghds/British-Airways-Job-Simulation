# British Airways Project

## 📌 Overview

This project was completed as part of the **British Airways Virtual Experience Program** on Forage. It focuses on data cleaning, exploratory data analysis (EDA), and insight generation based on airline customer reviews.

## 📂 Project Structure

```
├── British_Airways_Task1.ipynb        # Notebook for data scraping and cleaning
├── British_Airways_Task2.ipynb        # Notebook for EDA and visualizations
├── British_Airways_Data.csv           # Scraped and cleaned customer reviews data
├── customer_booking.csv               # Provided dataset with customer booking details
├── README.md                          # Project documentation
```

## 📊 Datasets

The project utilizes two primary datasets:

1. **British_Airways_Data.csv**  
   - Scraped customer reviews from Skytrax.
   - Contains fields like Name, Location, Date, Review Title, Full Review Text, Rating, and Service Attributes.

2. **customer_booking.csv**  
   - Provided customer data including:
     - **Booking Details**
     - **Revenue Information**
     - **Customer Behavior Attributes**

## 🚀 Installation

### 1️⃣ Clone the repository:

```bash
git clone https://github.com/ranjansinghds/British-Airways-Project
cd British-Airways-Project
```

### 2️⃣ Install dependencies:

Ensure you have the following Python packages installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `wordcloud`
- `scikit-learn` *(optional for deeper analysis)*

Install them with:

```bash
pip install requests pandas numpy matplotlib seaborn wordcloud scikit-learn
```

## 🔍 Methodology

### 1. **Data Cleaning**

- **Handling Missing Data**: Identified and removed/replaced missing values.
- **Feature Engineering**: Extracted and structured fields like Travel Class, Type of Traveller, Seat Type, etc.

### 2. **Exploratory Data Analysis (EDA)**

- **Review Sentiment Analysis**: Analyzed review text to understand customer sentiment trends.
- **Ratings Distribution**: Explored how different customer ratings are distributed.
- **Top Complaints & Praise**: Word clouds and frequency analysis of key themes.
- **Class of Travel Analysis**: Studied ratings across Economy, Premium Economy, Business, and First Class.

## 📊 Visualizations

Some visualizations generated during the analysis include:

![alt text](https://github.com/ranjansinghds/British-Airways-Project/blob/main/British_Airways_Task1_Png/British_Airways_Histogram.png)
![alt text](https://github.com/ranjansinghds/British-Airways-Project/blob/main/British_Airways_Task1_Png/Rating.png)
![alt text](https://github.com/ranjansinghds/British-Airways-Project/blob/main/British_Airways_Task1_Png/Seat%20Type.png)
![alt text](https://github.com/ranjansinghds/British-Airways-Project/blob/main/British_Airways_Task1_Png/Full%20review%20sentences%20wordcloud.png)

## 🛠️ Technologies Used

- **Python**
- **Pandas & NumPy** (for data manipulation)
- **Matplotlib & Seaborn** (for visualization)
- **WordCloud** (for textual analysis)
- **Jupyter Notebook**

## 📌 Future Improvements

- **Sentiment Modeling**: Build machine learning models to predict customer satisfaction.
- **Dashboarding**: Develop interactive dashboards using Tableau, Power BI, or Plotly Dash for management reporting.