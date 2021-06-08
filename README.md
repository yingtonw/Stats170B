# Stats170B
How the Severity of COVID-19 Affects People's Sentiment About it

1. Visualization.ipynb

A Jupyter Notebook file, including python codes to plot the line plots, correlation plots for our COV-19 data and Reddit comments. It helps us to understand our data set more. To run this file, you can open it into Jupyter Notebook and use the national-history.csv and comments_byDate.csv.

2. Visualization.html

The html version for Visualization.ipynb

3. collect_data.ipynb

A Juprter Notebook file, including python codes to crawl Reddit comments from different subReddits. And save them into one dataframe.

4. collect_data.html

The html version for collect_data.ipynb

5. data_cleaning.ipynb

A Jupyter Notebook file to clean the raw data sets. We deleted comments which are less than 10 words and delete the similar comments. Use SampleRedditComments.csv (The real Reddit Comment table is much larger)

6. data_cleaning.html

The html version for data_cleaning.ipynb

7. classification_model.ipynb

A Jupyter Notebook file for classification models, including KNN, RandomRorest and DecisionTree. We fit and evaluate the models. Use combined_index.csv

8. classification_model.html

The html version for classification_model.ipynb

9. time_series_model.ipynb

A Jupyter Notebook file for ARIMA models, including fitting and evaluating. Use combined_index.csv

10. time_series_model.html

The html version for time_series_model.ipynb
