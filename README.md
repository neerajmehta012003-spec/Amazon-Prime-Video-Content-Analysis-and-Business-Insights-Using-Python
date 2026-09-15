# Amazon Prime Video Content Analysis and Business Insights Using Python

Collab project link - https://colab.research.google.com/drive/1jQonHr9Tv6jNYIc8iHBGXiYS_3qxBs-d?usp=sharing
## Project Overview

This project performs an end-to-end exploratory data analysis of Amazon Prime Video's content catalog to identify meaningful patterns, trends, and business insights.

The analysis focuses on understanding the composition of the Prime Video library, including content types, genres, ratings, release years, countries, and other relevant attributes.

The project uses Python-based data analysis and visualization techniques to transform raw content data into actionable insights that could support content strategy and business decision-making.

---

## Objectives

The key objectives of this project are:

* Understand the structure and characteristics of the Amazon Prime Video content catalog.
* Perform data cleaning and preprocessing.
* Identify missing, duplicate, and inconsistent values.
* Analyze the distribution of Movies and TV Shows.
* Analyze genre and rating distributions.
* Examine content release trends over time.
* Identify countries contributing content to the platform.
* Explore relationships between important variables.
* Create meaningful visualizations to communicate findings.
* Derive business-oriented insights from the analysis.

---

## Dataset

The dataset contains information about Amazon Prime Video titles and includes attributes related to:

* Title
* Content type
* Director
* Cast
* Country
* Date added
* Release year
* Rating
* Duration
* Genres
* Description

The dataset was cleaned and transformed before performing exploratory analysis.

> **Note:** The original dataset is not included in this repository if it is subject to external ownership or size limitations. Refer to the project notebook for the dataset structure and analysis workflow.

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn

### Development Environment

* Google Colab
* Jupyter Notebook

---

## Project Workflow

The project follows an end-to-end data analysis workflow:

### 1. Data Loading

The dataset was imported into Python using Pandas and initially inspected to understand its structure.

### 2. Data Understanding

The dataset was examined using:

* Shape
* Data types
* Statistical summaries
* Unique values
* Missing-value analysis
* Duplicate-value analysis

### 3. Data Cleaning

Data preprocessing included:

* Handling missing values
* Removing duplicate records
* Correcting inconsistent values
* Converting columns into appropriate data types
* Cleaning categorical information
* Preparing data for analysis

### 4. Exploratory Data Analysis

The analysis examined:

* Movies vs. TV Shows
* Genre distribution
* Content ratings
* Release-year trends
* Country-wise content distribution
* Duration patterns
* Content availability trends

### 5. Data Visualization

Multiple visualizations were created to identify trends and communicate insights effectively.

The project uses charts such as:

* Bar charts
* Count plots
* Histograms
* Line charts
* Box plots
* Heatmaps
* Distribution plots

---

## Key Business Questions

The analysis addresses questions such as:

1. What type of content dominates the Amazon Prime Video catalog?
2. Which genres are most common?
3. Which content ratings are most prevalent?
4. How has content production changed over the years?
5. Which countries contribute the most content?
6. What is the distribution of movie durations?
7. How does the platform's content portfolio vary across different categories?
8. What trends can be identified from the available content data?
9. What business insights can be derived from the analysis?

---

## Key Insights

The analysis provides insights into:

* The overall composition of Amazon Prime Video's content library.
* The relative proportion of Movies and TV Shows.
* The most frequently represented genres.
* The distribution of content ratings.
* Changes in content availability across release years.
* Geographic distribution of available content.
* Characteristics and duration patterns of different types of content.

> **Note:** Specific numerical findings and visual evidence are available in the project notebook.

---

## Business Insights

The analysis can help understand potential content strategy considerations such as:

* Identifying high-volume content categories.
* Understanding audience-oriented rating patterns.
* Recognizing popular genres within the catalog.
* Evaluating geographic diversity.
* Understanding how the content portfolio has evolved over time.
* Identifying potential areas for content expansion or optimization.

These insights demonstrate how exploratory data analysis can support data-driven business decisions.

---

## Project Structure

```text
amazon-prime-video-content-analysis/
│
├── README.md
├── amazon_prime_video_analysis.ipynb
│
├── images/
│   ├── content_type_distribution.png
│   ├── genre_distribution.png
│   ├── rating_distribution.png
│   ├── release_year_trend.png
│   └── correlation_heatmap.png
│
└── data/
    └── README.md
```

---

## How to Run the Project

### Option 1 — Google Colab

Open the notebook in Google Colab and execute the cells sequentially.

### Option 2 — Jupyter Notebook

Clone or download this repository and open the `.ipynb` file using Jupyter Notebook or JupyterLab.

Required libraries can be installed using:

```bash
pip install pandas numpy matplotlib seaborn
```

---

## Google Colab

The complete analysis was developed using Google Colab.

**[Open Project in Google Colab](PASTE_YOUR_COLAB_LINK_HERE)**

---

## Project Highlights

* End-to-end exploratory data analysis
* Data cleaning and preprocessing
* Missing-value and duplicate handling
* Univariate and multivariate analysis
* Statistical exploration
* Data visualization
* Business-oriented interpretation
* Actionable insights from entertainment content data

---


## Skills Demonstrated

This project demonstrates practical skills in:

* Python
* Pandas
* NumPy
* Data Cleaning
* Exploratory Data Analysis
* Data Visualization
* Statistical Analysis
* Business Analysis
* Insight Generation
* Data Storytelling

---

## Author

**Neeraj Mehta**

Aspiring Data Analyst | AI/ML Engineer

---

## Disclaimer

This project is created for educational and portfolio purposes. Amazon Prime Video and related trademarks belong to their respective owners.
