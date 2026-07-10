# Netflix-Data-Analysis
A data analytics project that explores Netflix movie data using Python, performing data cleaning, preprocessing, exploratory data analysis (EDA), and visualizations to uncover insights into movie ratings, popularity, genres, and release trends.

# 🎬 Netflix Movie Data Analysis

## 📌 Overview

This project focuses on analyzing a Netflix movie dataset using Python to uncover insights into movie popularity, ratings, genres, and release trends. The project demonstrates data cleaning, preprocessing, exploratory data analysis (EDA), and visualization techniques to transform raw data into meaningful business insights.

## 📂 Dataset

* **Dataset:** Netflix Movies Dataset (`mymoviedb.csv`)
* **Records:** ~9,800+ movies
* **Features:** Release Date, Title, Popularity, Vote Count, Vote Average, Genre, Overview, Original Language, Poster URL

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

## 📊 Project Workflow

### 1. Data Loading

* Imported dataset into Pandas DataFrame.
* Examined dataset structure and summary statistics.

### 2. Data Cleaning

* Removed missing values.
* Removed duplicate records.
* Converted data types:

  * Release Date → Date/Year
  * Vote Count → Integer
  * Vote Average → Float
* Removed unnecessary columns.

### 3. Data Preprocessing

* Extracted release year from the release date.
* Split multiple genres into individual records using `explode()`.
* Categorized movie ratings into:

  * Not Popular
  * Below Average
  * Average
  * Popular

### 4. Exploratory Data Analysis (EDA)

* Distribution of movie genres.
* Most popular movies.
* Highest-rated movies.
* Movies released by year.
* Vote count and popularity analysis.

### 5. Data Visualization

* Genre distribution.
* Movie release trends.
* Rating distribution.
* Popularity analysis using charts.

## 📈 Key Insights

* Identified the most popular movies based on popularity scores.
* Analyzed the distribution of movie genres.
* Explored release trends across different years.
* Categorized movies based on audience ratings.
* Examined voting patterns and popularity metrics.

## 📁 Project Structure

```text
Netflix-Movie-Data-Analysis/
│
├── mymoviedb.csv
├── Netflix Data Analysis.ipynb
├── README.md
└── images/ (optional)
```

## 🚀 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Data Transformation
* Data Visualization
* Python Programming
* Statistical Analysis

## Screenshot

https://github.com/shreyashshinde0910-max/Netflix-Data-Analysis/blob/main/Top%2010%20Movies.png
https://github.com/shreyashshinde0910-max/Netflix-Data-Analysis/blob/main/SS_2.png
https://github.com/shreyashshinde0910-max/Netflix-Data-Analysis/blob/main/SS_3.png
