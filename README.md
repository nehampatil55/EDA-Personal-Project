# EDA-Personal-Project
Disney+ Movies and TV show data Aalysis

**Movies and TV Shows listings on Disney+  Dataset**
https://www.kaggle.com/shivamb/disney-movies-and-tv-shows?select=disney_plus_titles.csv

**About this Dataset**: Disney+ is another one of the most popular media and video streaming platforms. They have close to 1300 movies or tv shows available on their platform, as of mid-2021, they have over 116M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Amazon Prime, along with details such as - cast, directors, ratings, release year, duration, etc.

**Tools & Libraries**

• Python • Jupyter Notebook • Pandas • Numpy • Seaborn • Matplotlib • Plotly & Cufflinks

**Data Description**

show_id
type: Movie or TV Show
title: Movie or TV Show name
cast: Characters played role in movie or TV show
country: movie / TV show in country
date_added: data added in which year
release_year: which year movie is released
rating: movie/TV show rating
duration: in minutes/ no.of seasons
listed_in: genre
description: Movie /TV show description


**
Exploratory Data Analysis**

**Data Cleaning**

After importing libraries and loading dataset into notebook, I had following data cleaning process
Check head and tail. Then shape of dataset and info .
It has 1450 rows and 12 columns. And also checked for data types. release_year is showing int data type . remaining all are having object data type.
For missing values in country, I used mode country to replace missing values. Delete director, cast and date added columns which are not required for analysis.
Made 2 separate columns for duration and seasons. And converted them into int datatype.
Finally dropped ‘rating’ missing values
Now we have dataset of 1447 rows and 10 columns. No missing values. No duplicate data
All set to do analysis.

**Visualizations:**

1.	Which content available on Disney+  ?
2.	Release Year Analysis
3.	Content Ratings Analysis
4.	Country Analysis
5.	Genre of Movies and TV shows

