# 🚗 Cars24 Market Analysis — Web Scraping & EDA

## 📌 Overview

This project focuses on **web scraping, data cleaning, and exploratory data analysis (EDA)** of used-car listings from **Cars24**.

The objective is to collect real-world used-car data and analyze important factors such as **price, brand, model, manufacturing year, kilometers driven, fuel type, transmission, ownership, and location** to understand trends in the used-car market.

---

## 🎯 Objectives

* Scrape used-car listing data from Cars24.
* Clean and preprocess the scraped dataset.
* Perform exploratory data analysis (EDA).
* Analyze factors affecting used-car prices.
* Identify popular brands and car models.
* Understand the relationship between price, mileage, and vehicle age.
* Analyze fuel type, transmission, and ownership trends.
* Create meaningful visualizations from the collected data.

---

## 🛠️ Technologies & Libraries

| Technology                  | Purpose                   |
| --------------------------- | ------------------------- |
| 🐍 Python                   | Programming Language      |
| 🌐 BeautifulSoup / Selenium | Web Scraping              |
| 🐼 Pandas                   | Data Cleaning & Analysis  |
| 🔢 NumPy                    | Numerical Operations      |
| 📊 Matplotlib               | Data Visualization        |
| 📈 Seaborn                  | Statistical Visualization |
| 📓 Jupyter Notebook         | Analysis                  |

---

## 🔄 Project Workflow

```text
Cars24 Website
      ↓
Web Scraping
      ↓
Raw Data Collection
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Data Visualization
      ↓
Market Insights
```

---

## 📊 Dataset

The dataset contains information collected from Cars24 used-car listings.

### Key Features

* **Brand** – Car manufacturer
* **Model** – Car model
* **Price** – Listed selling price
* **Year** – Manufacturing/registration year
* **Kilometers Driven** – Distance driven by the vehicle
* **Fuel Type** – Petrol, Diesel, CNG, Electric, etc.
* **Transmission** – Manual / Automatic
* **Ownership** – First owner, second owner, etc.
* **Location** – City/location of the listing

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

* Handling missing values
* Removing duplicate records
* Converting price and mileage into numerical formats
* Standardizing categorical variables
* Handling inconsistent values
* Detecting potential outliers
* Creating derived variables where required

---

## 🔍 Exploratory Data Analysis

The project analyzes several important questions:

### 💰 Price Analysis

* What is the distribution of used-car prices?
* Which brands have the highest average prices?
* Which models fall into different price segments?

### 🚘 Brand & Model Analysis

* Which brands have the highest number of listings?
* Which car models are most common?
* How does pricing vary between brands?

### 📅 Vehicle Age vs Price

Analyzes how the age of a vehicle affects its resale price and helps identify depreciation patterns.

### 🛣️ Mileage vs Price

Studies the relationship between kilometers driven and the listed price of a vehicle.

### ⛽ Fuel Type Analysis

Compares the availability and pricing of:

* Petrol
* Diesel
* CNG
* Electric
* Other available fuel types

### ⚙️ Transmission Analysis

Compares **manual and automatic** vehicles based on:

* Number of listings
* Average price
* Price distribution

### 👤 Ownership Analysis

Examines how the number of previous owners relates to the price of used vehicles.

---

## 📈 Visualizations

The project includes visualizations such as:

* 📊 Price distribution
* 📊 Brand-wise listing count
* 📊 Average price by brand
* 📈 Price vs. kilometers driven
* 📈 Price vs. vehicle age
* 🥧 Fuel-type distribution
* 📊 Transmission distribution
* 📦 Boxplots for price comparison
* 🔥 Correlation heatmap
* 📊 Ownership-wise price analysis

---

## 💡 Key Insights

The analysis helps identify patterns in the used-car market and understand how different vehicle characteristics influence pricing.

Some of the major areas of insight include:

* Relationship between **vehicle age and resale price**
* Impact of **kilometers driven** on price
* Differences in pricing across **car brands and models**
* Market distribution of different **fuel types**
* Pricing differences between **manual and automatic cars**
* Effect of **ownership history** on resale value

```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Cars24-Market-Analysis.git
```

### 2. Navigate to the Project Directory

```bash
cd Cars24-Market-Analysis
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Notebook

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
notebooks/Cars24_EDA.ipynb
```

---

## 🔮 Future Scope

This project can be further extended by:

* 🤖 Building a **car price prediction model**
* 📊 Creating an interactive **Power BI / Tableau dashboard**
* 🔎 Comparing Cars24 with other used-car platforms
* 📈 Performing advanced statistical analysis
* 🧠 Developing a used-car recommendation system
* 🚀 Deploying a machine-learning model for real-time price prediction

---

## ⚠️ Disclaimer

This project is created for **educational and data-analysis purposes**. The scraped data represents listings available at the time of data collection and may change over time.

---

## 👨‍💻 Skills Demonstrated

```text
Python
Web Scraping
Data Collection
Data Cleaning
Exploratory Data Analysis
Data Visualization
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Business Analytics
```

---

## ⭐ Conclusion

The **Cars24 Market Analysis** project demonstrates an end-to-end data analytics workflow — from **web scraping and data collection to data cleaning, exploratory analysis, visualization, and business insights**.

This project provides practical experience in working with real-world data and understanding the factors that influence the **used-car market and vehicle pricing**.

⭐ If you find this project useful, consider giving the repository a star!
