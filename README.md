# 🎮 Game Zone Analytics

## 📌 Project Overview

**Game Zone Analytics** is a Power BI-based data analytics project designed to analyze **50,000 games** across different genres, platforms, regions, and years.

The project focuses on understanding game distribution, sales performance, player engagement, and ratings to identify important market trends and business insights.

---

## 🎯 Business Problem

The gaming industry generates large amounts of data across multiple dimensions such as genre, platform, region, sales, player count, and ratings.

The objective of this project is to transform raw gaming data into meaningful insights that can help understand:

* Which genres perform best?
* Which platforms generate the highest sales?
* Which regions show stronger game performance?
* How does game performance change over time?
* Which combinations of genre, platform, and region perform best?

---

## 🎯 Project Objectives

* Analyze the distribution of games across genres and platforms.
* Compare sales performance across different categories.
* Analyze player count and rating patterns.
* Identify regional performance trends.
* Analyze year-wise gaming trends.
* Perform cross-analysis between genres, platforms, and regions.
* Build an interactive and professional Power BI dashboard.
* Generate actionable business insights from the analysis.

---

## 🔄 Project Workflow

```text
Raw Data
   ↓
Data Preparation & Validation
   ↓
Exploratory Data Analysis (EDA)
   ↓
Dashboard Development
   ↓
Dashboard Validation
   ↓
Insights & Recommendations
```

---

## 📊 Dataset

**Dataset:** `rea_games_dataset_updated.csv`

**Number of Records:** 50,000 Games

The dataset contains information related to:

* Game
* Genre
* Platform
* Region
* Sales
* Player Count
* Rating
* Year

---

## 📈 Exploratory Data Analysis

The EDA phase analyzed the dataset across multiple dimensions:

### Genre Analysis

* Number of Games by Genre
* Total Sales by Genre
* Average Sales by Genre
* Average Player Count by Genre
* Average Rating by Genre

### Platform Analysis

* Number of Games by Platform
* Total Sales by Platform
* Average Sales by Platform
* Average Player Count by Platform
* Average Rating by Platform

### Regional Analysis

* Number of Games by Region
* Total Sales by Region
* Average Sales by Region
* Average Player Count by Region
* Average Rating by Region

### Time-Based Analysis

* Number of Games by Year
* Total Sales by Year
* Average Sales by Year
* Average Player Count by Year
* Average Rating by Year

### Cross-Analysis

* Genre × Platform Sales
* Genre × Region Sales
* Platform × Region Sales
* Genre × Average Rating

---

## 📊 Power BI Dashboard

The final dashboard contains the following pages:

### 1. Executive Overview

Provides a high-level summary using KPI cards and key visuals.

**KPIs:**

* Total Games
* Total Sales
* Average Player Count
* Average Rating

### 2. Genre Performance

Analyzes game performance across different genres using sales, ratings, player count, and game distribution.

### 3. Platform Performance

Compares gaming platforms based on games, sales, player count, and ratings.

### 4. Regional Performance

Analyzes game performance across different geographical regions.

### 5. Time-Based Performance

Examines gaming trends and performance across different years.

### 6. Cross-Analysis Performance

Provides deeper analysis by combining multiple dimensions such as genre, platform, and region.

---

## 🔍 Key Insights

* **Adventure × Mobile** has the highest sales among genre-platform combinations.
* **Shooter × South America** has the highest sales among genre-region combinations.
* **PS5** performs best across regions.
* **Adventure and Strategy** have the highest average ratings.
* **Xbox** has the highest total platform sales at **506,055**.
* **PS5** has the highest average sales at **50.42**.
* Average player count is **25 across all analyzed genres and platforms**.
* Overall sales and ratings are relatively balanced across major genres and platforms.

---

## 💡 Business Recommendations

* Focus on **Adventure games on Mobile**, given their strong sales performance.
* Investigate the factors contributing to the strong performance of **Shooter games in South America**.
* Consider **PS5** as a strong platform for game performance and market opportunities.
* Maintain a balanced portfolio across genres while giving additional attention to high-performing genres such as **Adventure and Strategy**.
* Use regional and platform-level insights to support targeted marketing and distribution strategies.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI** — Data cleaning, analysis, visualization, and dashboard development
* **Power Query** — Data transformation and validation
* **DAX** — Measures and KPI calculations
* **Microsoft PowerPoint** — Dashboard presentation

---

## 📁 Project Folder Structure

```text
D:\Real_Life_Problems\Game_Zone_Analytics
│
├── data
│   └── rea_games_dataset_updated.csv
│
├── PowerBI_File
│   └── GZA1.pbix
│
├── Screenshots
│   ├── 1_Executive_Overview.png
│   ├── 2_Genre_Performance.png
│   ├── 3_Platform_Performance.png
│   ├── 4_Regional_Performance.png
│   ├── 5_Time_Based_Performance.png
│   └── 6_Cross_Analysis_Performance.png
│
└── requirements.txt
```

---

## 📸 Dashboard Screenshots

### Executive Overview

![Executive Overview](Screenshots/1_Executive_Overview.png)

### Genre Performance

![Genre Performance](Screenshots/2_Genre_Performance.png)

### Platform Performance

![Platform Performance](Screenshots/3_Platform_Performance.png)

### Regional Performance

![Regional Performance](Screenshots/4_Regional_Performance.png)

### Time-Based Performance

![Time-Based Performance](Screenshots/5_Time_Based_Performance.png)

### Cross-Analysis Performance

![Cross-Analysis Performance](Screenshots/6_Cross_Analysis_Performance.png)

---

## 📂 Project Files

* **Dataset:** `data/rea_games_dataset_updated.csv`
* **Power BI Dashboard:** `PowerBI_File/GZA1.pbix`
* **Dashboard Presentation:** `PPT_Dashboard_Presentation/GZA1.pptx`
* **Dashboard Screenshots:** `Screenshots/`
* **Dependencies:** `requirements.txt`

---

## 🚀 Conclusion

Game Zone Analytics transforms a 50K-game dataset into an interactive Power BI dashboard that provides insights into **game genres, platforms, regions, sales, player engagement, ratings, and time-based trends**.

The project demonstrates practical skills in **data preparation, exploratory data analysis, DAX, Power BI visualization, dashboard development, and business insight generation**.
