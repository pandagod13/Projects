# Spotify EDA Project

This project performs an exploratory data analysis (EDA) on a dataset of Spotify songs. The analysis includes data understanding, preparation, descriptive statistics, popularity analysis, audio feature exploration, lyrics-based analysis, temporal trends, genre & artist insights, and outlier detection.

## Project Structure

- **Data Understanding & Preparation**: Load and inspect the data using Pandas. Check the shape, data types, and missing values. Create a table summarizing features and handle missing data.
- **Descriptive Statistics**: Calculate mean, median, range, and standard deviation for numerical features. Visualize distributions using histograms, boxplots, or density plots. Count unique values and frequencies for categorical features and visualize distributions using bar plots or pie charts.
- **Popularity Analysis**: Plot a histogram of Popularity Score to see if it’s skewed. Create a heatmap of correlations between popularity and audio features. Use scatterplots to explore relationships like Popularity vs. Loudness or Tempo. Group by Genre or Artist and plot average popularity.
- **Audio Feature Exploration**: Use pair plots or scatter matrices to explore interactions between audio features. Use PCA or t-SNE to reduce audio features to 2D and color-code by genre/popularity. Compare average Energy or Acousticness across genres using boxplots.
- **Lyrics-Based Analysis**: Use NLP libraries like TextBlob to analyze lyric sentiment and compare sentiment scores with Valence. Generate word clouds for lyrics of top-popularity vs. low-popularity songs.
- **Temporal Trends**: Create a line chart of average Popularity or Tempo over time. Identify trends such as 'Songs released in 2020 are louder'. Compare features between older and newer songs.
- **Genre & Artist Insights**: Sort genres by average popularity and visualize with a horizontal bar chart. Identify artists with the most songs in the dataset. Check if songs with multiple artists are more popular.
- **Outlier Detection**: Find songs with extreme values and explore if outliers are valid or errors.

## How to Run

1. Ensure you have Python 3 installed.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook `Spotify_Eda.ipynb` to perform the analysis.

## Requirements

- pandas
- seaborn
- matplotlib
- textblob
- wordcloud
- scikit-learn
- nltk

## Results

The analysis provides insights into the characteristics of popular songs, trends over time, and differences between genres and artists. It also highlights the importance of audio features and lyrics in determining a song's popularity.

## Conclusion

This project demonstrates the use of EDA techniques to uncover patterns and insights in a dataset of Spotify songs. The findings can be used to inform further analysis or model development for predicting song popularity.

## Further Analysis

- **Predictive Modeling**: Develop machine learning models to predict song popularity based on audio features, lyrics sentiment, and other metadata.
- **Time Series Analysis**: Perform a more detailed time series analysis to understand trends and seasonality in song releases and popularity.
- **Genre-Specific Analysis**: Conduct separate analyses for different genres to uncover unique patterns and trends within each genre.
- **Artist Collaboration Impact**: Investigate the impact of artist collaborations on song popularity and explore network analysis of artist collaborations.
- **Listener Demographics**: If available, incorporate listener demographic data to analyze how different age groups, genders, and regions influence song popularity.
- **Advanced NLP Techniques**: Use advanced natural language processing techniques to perform deeper sentiment analysis and topic modeling on song lyrics.
- **Streaming Patterns**: Analyze streaming patterns and user behavior to understand how listening habits affect song popularity over time.

