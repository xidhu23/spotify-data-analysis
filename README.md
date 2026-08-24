# spotify-data-analysis
Exploratory data analysis of Spotify tracks and artists using Python, Pandas, Matplotlib and Seaborn.
## Project Overview

This project focuses on analyzing Spotify track and artist data using Python. The objective is to explore song popularity, audio characteristics, release trends, song duration, and genre-level patterns.

The analysis was performed using Python with Pandas, NumPy, Matplotlib, and Seaborn.

## Objectives

- Explore the Spotify tracks and artists datasets
- Identify the most and least popular songs
- Perform data cleaning and preprocessing
- Analyze relationships between audio features
- Study song releases across different years
- Analyze song duration
- Combine track and artist datasets
- Analyze genres based on duration and popularity
- Create visualizations to communicate insights

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The project uses two datasets:

- `tracks.csv` – Contains information about Spotify tracks, including popularity, duration, release date, energy, loudness, acousticness, and other audio features.
- `artists.csv` – Contains artist information including artist IDs and genres.

## Analysis Performed

### 1. Exploratory Data Analysis

The datasets were explored using:

- `head()`
- `isnull()`
- `info()`
- `describe()`

This was used to understand the structure, data types, missing values, and statistical characteristics of the data.

### 2. Song Popularity Analysis

The analysis identifies:

- 10 least popular songs
- Highly popular songs with popularity scores above 90

### 3. Data Preprocessing

Several transformations were performed:

- Converted release dates into datetime format
- Extracted release years
- Converted song duration from milliseconds to seconds
- Cleaned artist IDs before merging datasets

### 4. Correlation Analysis

A Pearson correlation heatmap was created to understand relationships between numerical variables in the Spotify dataset.

### 5. Regression Analysis

Regression plots were created to investigate:

- Loudness vs. Energy
- Popularity vs. Acousticness

### 6. Year-wise Analysis

The project analyzes:

- Number of songs released per year
- Song duration across different years

### 7. Artist and Genre Analysis

The tracks and artists datasets were merged using artist IDs.

Genre-level analysis was then performed to study:

- Total song duration by genre
- Genre popularity

## Visualizations

The project includes:

- Correlation heatmap
- Regression plots
- Distribution plot
- Bar charts
- Genre analysis charts

## Key Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Transformation
- Data Filtering and Sorting
- GroupBy Analysis
- Data Merging
- Correlation Analysis
- Regression Analysis
- Data Visualization
- Python for Data Analytics

