# Netflix-Dataset
📊 Project Overview
This project explores and analyzes the Netflix Dataset (2021) containing 9,425 titles and 29 features.
It focuses on cleaning, analyzing, and visualizing the dataset to uncover insights about movies, series, genres, IMDb ratings, awards, and box office performance.

📂 Dataset Information
Dataset Name: Netflix Dataset Latest 2021.csv
Total Entries: 9,425
Total Columns: 29

Key Columns Include:

🎞️ Title, Genre, Languages, Series or Movie
⭐ IMDb Score, Rotten Tomatoes Score, Metacritic Score
🏆 Awards Received, Awards Nominated For
💰 Box Office Earnings
🌍 Country Availability
📅 Release Date & Netflix Release Date
⚙️ Technologies Used
Python
Pandas – Data manipulation
NumPy – Numerical operations
Matplotlib – Data visualization
Seaborn – Statistical visualization
Google Colab / Jupyter Notebook
🔍 Data Cleaning Steps
Filled missing categorical values with "Unknown".
Converted Boxoffice values to numeric format.
Filled missing numeric values with median values.
Ensured proper datetime format for release date columns.
📈 Data Analysis Questions & Insights
1. Average IMDb Score
Average IMDb Score: ~6.96
Indicates that most Netflix content has good audience reception.
2. Movies vs Series
Counted and compared how many are movies vs series.
3. Total Box Office Collection
Summed all available Boxoffice data to estimate Netflix's financial scale.
4. IMDb Score vs Box Office
Calculated correlation to identify if better-rated movies perform better financially.
5. Top 5 Genres
Found the most frequent genres (e.g., Drama, Comedy, Romance).
6. Median Rotten Tomatoes Score
Median value used to avoid bias from outliers.
7. Top Directors
Directors ranked by highest average IMDb score.
8. Top Rated Movies
Extracted the top 10 movies by IMDb score.
9. Top Countries
Identified countries with the most Netflix content releases.
📊 Visualizations
🔹 Using Matplotlib & Seaborn:
Distribution of IMDb Scores – Histogram
Movies vs Series Count – Bar Chart
Netflix Releases Over the Years – Line & Bar Charts
IMDb Score vs Box Office – Scatter Plot
IMDb Score vs Awards Received – Regression Plot
Top Genres by IMDb Score – Bar Plot
🧠 Key Insights
Netflix has a diverse global presence across countries and languages.
IMDb scores remain consistent across years, showing steady content quality.
Box office earnings vary but show correlation with IMDb ratings.
Genres like Drama and Comedy dominate the platform.
Netflix continues to expand its yearly release count consistently.
🏁 Conclusion
This analysis provides data-driven insights into Netflix’s 2021 content library, helping understand trends in ratings, genres, and production.
The findings can assist in predicting audience preferences and improving content recommendations.

📁 Repository Structure
💡 Future Enhancements
Add interactive dashboards using Plotly or Power BI.
Perform machine learning analysis to predict IMDb scores.
Integrate genre-based recommendation system logic.
🖋️ License
This project is for educational purposes only.

⭐ If you like this project, give it a star on GitHub!
