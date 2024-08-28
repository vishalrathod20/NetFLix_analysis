# Netflix Content Analysis - Exploratory Data Analysis (EDA)

## Overview

This project provides a comprehensive analysis of Netflix’s content library. By examining various attributes of the available data, the project highlights trends in content types, genres, geographic distribution, maturity ratings, and other key factors that define Netflix’s offerings. The insights gained from this analysis can help understand Netflix’s content strategy and its appeal to diverse audiences worldwide.

## Objectives

- Analyze the distribution of content types (Movies vs. TV Shows) on Netflix.
- Identify the most prevalent genres and observe trends in genre popularity.
- Examine the geographic distribution of content production.
- Analyze content ratings to understand the target audience's age demographics.
- Explore the trends in content release over the years.
- Evaluate the duration of Movies and TV Shows to understand common patterns.
- Identify prominent actors and directors to understand industry collaborations.

## Datasets

The dataset used in this project contains information about Netflix’s content, including titles, genres, countries of production, maturity ratings, release dates, and durations. The data was obtained from [source of data, e.g., Kaggle Netflix dataset](#).

## Libraries Used

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations and array operations.
- **Matplotlib**: For creating visualizations and plots.
- **Seaborn**: For statistical data visualization.

## Data Cleaning

- Removed duplicates and missing values to ensure data quality.
- Standardized column names and formats for consistency.
- Handled missing values in critical columns like `Country`, `Genre`, and `Director`.
- Converted date columns to appropriate datetime formats.
- Extracted and normalized nested data (e.g., genres, countries) for analysis.

## Key Findings

1. **Content Type Distribution**: Movies are more prevalent than TV Shows on Netflix.
2. **Popular Genres**: Dramas, Comedies, and Documentaries dominate the content library.
3. **Geographic Insights**: The United States leads content production, with significant contributions from India and the United Kingdom. Increasing content from Japan, South Korea, and Brazil indicates Netflix’s expanding global reach.
4. **Maturity Ratings**: TV-MA (mature content) is the most common rating, suggesting a strong focus on adult audiences. However, family-friendly content is also present.
5. **Release Trends**: Content releases have increased over the years, with notable spikes towards the end of the year, targeting holiday viewership.
6. **Duration Patterns**: Movies typically run for 90 to 120 minutes, while TV Shows exhibit a wide range of episode lengths.
7. **Industry Collaborations**: Frequent appearances by prominent actors and directors suggest successful partnerships and consistent quality in content production.

## Visualizations

- Bar charts showing the distribution of content types and genres.
- Geographic heatmaps to visualize content production across different countries.
- Time series plots depicting content release trends over the years.
- Pie charts and bar graphs illustrating the breakdown of maturity ratings.
- Word clouds to highlight popular actors and directors.

## Conclusion

The analysis provides valuable insights into Netflix’s content strategy, highlighting its focus on a diverse range of genres and catering to both mature and family-friendly audiences. By leveraging this analysis, stakeholders can make informed decisions to optimize content offerings and enhance user engagement.

## Future Work

- Extend the analysis to include user ratings and reviews to assess content popularity and quality.
- Investigate the impact of Netflix Originals on the platform's growth and user retention.
- Explore sentiment analysis on movie and show descriptions to identify content appeal.

## How to Use

1. Clone the repository: `git clone [https://github.com/vishalrathod20/NetFLix_analysis.git]`
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the Jupyter Notebook: `jupyter notebook Netflix_EDA.ipynb`

