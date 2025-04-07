# Elevate-lab-task1

# Netflix Movies and TV Shows - Data Cleaning Task

## 🔧 Objective
Cleaned and prepared a raw Netflix dataset by handling missing values, duplicates, and formatting inconsistencies.

## 📂 Dataset Columns
- show_id
- type
- title
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in
- description

## 🔍 Data Cleaning Steps
1. Filled missing:
   - director → 'Unknown'
   - cast → 'Not Specified'
   - country → 'Unknown'
   - date_added, rating, duration → filled with most frequent values
2. Removed duplicates
3. Standardized column names (snake_case, lowercase)
4. Converted date_added to datetime format
5. Saved cleaned dataset as netflix_titles_cleaned.csv

