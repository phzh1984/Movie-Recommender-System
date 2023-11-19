# Movie-Recommender-System

Overview

This GitHub repository contains a Movie Recommender System based on the TMDB 5000 Movie Data. The dataset includes metadata on approximately 5,000 movies, providing information such as plot details, cast, crew, budget, and revenues. The goal of this project is to explore the factors that contribute to the success of a movie before its release, including predicting high ratings and commercial success.

Data Source

Due to a DMCA takedown request from IMDb, the original dataset was replaced with a similar set of films and data fields from The Movie Database (TMDb), following their terms of use. The new dataset includes full credits for both the cast and crew, with actors and actresses listed in the order they appear in the credits. Revenues are more up-to-date compared to IMDb figures, providing a more accurate representation of a film's global earnings.

Changes in Data Fields

Several new columns have been introduced in the dataset, such as homepage, id, original_title, overview, popularity, production_companies, production_countries, release_date, spoken_languages, status, tagline, and vote_average. Some columns from the original dataset, including actor Facebook likes, aspect ratio, color, content rating, director Facebook likes, face number in the poster, movie Facebook likes, movie IMDb link, num critic for reviews, and num user for reviews, have been removed.

Data Consistency

It's important to note that all fields in the dataset are filled out by users, leading to potential inconsistencies in keywords, genres, ratings, and other attributes. Additionally, some fields like runtime may not be consistent across versions of the dataset.

Users can explore the provided code to understand how to load and manipulate the data effectively. The project aims to help answer questions related to predicting movie success and understanding the factors influencing ratings and commercial performance.


