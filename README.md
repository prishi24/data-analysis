# 📊 Netflix Movies and TV Shows Dataset

This project contains a synthetic dataset of over **300 Netflix movies and TV shows**. It is designed for use in **data analysis**, **visualization**, **data cleaning**,
or as a **practice dataset** for data analyst learners.

## 📁 Dataset File

- **Filename**: `netflix_movies_tv_shows.csv`
- **Rows**: 300+
- **Format**: CSV (Comma Separated Values)

## 📌 Features (Columns)

| Column Name   | Description |
|---------------|-------------|
| `show_id`     | Unique ID for each entry (e.g., s1, s2...) |
| `type`        | Whether it's a Movie or a TV Show |
| `title`       | Title of the show or movie |
| `director`    | Director's name (blank for many TV shows) |
| `cast`        | Main actors or actresses |
| `country`     | Country of origin |
| `date_added`  | Date it was added to Netflix |
| `release_year`| Year the content was originally released |
| `rating`      | Age rating (TV-MA, PG, R, etc.) |
| `duration`    | Length of movie or number of seasons |
| `listed_in`   | Genre(s) the content falls under |
| `description` | Short summary of the content |

## process:
1. Handling missing values
2. Removing duplicate values
3. Converting date formats
4. Adding filter to access dataset uniformly.
