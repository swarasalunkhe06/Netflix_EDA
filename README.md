# 🎬 Netflix Movies and TV Shows – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Netflix Movies and TV Shows dataset using Python. The objective is to explore Netflix's content library, identify patterns and trends, and generate meaningful business insights through data analysis and visualization.

The analysis explores content distribution, release trends, country-wise contributions, popular genres, maturity ratings, TV show seasons, and more.

## 🎯 Project Objectives

- Analyze the distribution of Movies and TV Shows on Netflix.
- Identify yearly and monthly content addition trends.
- Explore country-wise content distribution.
- Identify the most popular genres and categories.
- Analyze content maturity ratings.
- Understand TV Shows based on the number of seasons.
- Examine the time gap between original release and Netflix addition.
- Compare genre distribution between Movies and TV Shows.
- Generate meaningful business insights and recommendations.

## 📂 Dataset Information

The dataset contains information about Netflix Movies and TV Shows.

**Key Columns:**
- `show_id` – Unique identifier for each title.
- `type` – Movie or TV Show.
- `title` – Title name.
- `director` – Director of the content.
- `cast` – Actors and actresses.
- `country` – Country of production.
- `date_added` – Date the title was added to Netflix.
- `release_year` – Original release year.
- `rating` – Content maturity rating.
- `duration` – Movie runtime or TV Show seasons.
- `listed_in` – Genre or category.
- `description` – Content description.

## 🛠️ Tools & Technologies

- **Python** – Programming language
- **Pandas** – Data manipulation and cleaning
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Development environment

## 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Checked dataset structure, data types and duplicate records.
- Analyzed missing values.
- Converted `date_added` into datetime format.
- Handled missing values in Director, Cast, Country and Rating columns.
- Removed records with missing `date_added` and `duration`.
- Extracted year and month from the date column.
- Created additional columns for content analysis.

## 📊 Exploratory Data Analysis

The project includes 13 analytical questions:

1. What type of content dominates Netflix?
2. How has the composition of Netflix content changed across release years?
3. Which months have the highest number of Netflix additions?
4. Did Netflix add more Movies or TV Shows in different years?
5. Which countries contribute the most titles to Netflix's catalogue?
6. Which countries contribute more Movies and which contribute more TV Shows?
7. What genres are most frequently represented in Netflix's catalogue?
8. What content ratings are most common on Netflix?
9. How many seasons do most Netflix TV Shows have?
10. How long after their original release were titles added to Netflix?
11. Which decades contribute the most Movies and TV Shows to Netflix?
12. Which directors have the highest number of titles in the dataset?
13. How do genres compare between Movies and TV Shows?

## 💡 Key Insights

- Movies account for approximately **69.68%** of the Netflix catalogue, while TV Shows represent **30.32%**.
- **2019** was the peak year for Netflix content additions in the dataset.
- **July** recorded the highest number of content additions.
- The **United States** is the largest contributing country.
- **International Movies** are the most represented genre category.
- **TV-MA** is the most common maturity rating.
- **One season** is the most common TV Show duration.
- The median time gap between a title's release and its addition to Netflix is **1 year**.

## 📈 Visualizations

The project uses multiple visualization techniques, including:

- Donut and pie charts
- Bar charts
- Horizontal bar charts
- Line charts
- Stacked bar charts
- Histograms
- Comparative genre visualizations

A consistent Netflix-inspired visualization theme was used throughout the project.

## 📁 Project Structure

```text
Netflix-EDA/
│
├── Netflix_EDA.ipynb
├── netflix_data.csv
└── README.md
```

## 🚀 How to Run the Project

1. Clone this repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

2. Navigate to the project folder:

```bash
cd Netflix-EDA
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Netflix_EDA.ipynb` and run the cells.

**Note:** Keep `netflix_data.csv` in the same folder as the notebook.

## 🎯 Conclusion

This project demonstrates how Exploratory Data Analysis can be used to understand Netflix's content catalogue and uncover meaningful patterns.

By analyzing content types, geographical distribution, genres, release trends and maturity ratings, the project provides useful insights into Netflix's content composition and opportunities for catalogue diversification.

The project helped strengthen practical skills in Python, data cleaning, exploratory analysis, data visualization and business insight generation.

---

**Author:** Swara

**Project Type:** Exploratory Data Analysis (EDA)

**Domain:** Data Analytics | Entertainment

