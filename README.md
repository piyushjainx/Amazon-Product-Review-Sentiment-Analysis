# Amazon-Product-Review-Sentiment-Analysis

# Introduction:
This project is focused on performing sentiment analysis on Amazon product reviews. Sentiment analysis, also known as opinion mining, is the process of determining the sentiment expressed in a piece of text, whether it's positive, negative, or neutral. In this project, we aim to analyze customer reviews of Amazon products to gain insights into how customers feel about the products they have purchased.

# Dataset:
The dataset used in this project is a collection of Amazon product reviews, which is available in a CSV file format. The dataset contains information about customer reviews, including the product ID, review text and a score rating provided by the customers. To start the analysis, we perform the following steps:

1. **Data Loading**: The dataset is loaded using the Pandas library, which allows us to read and manipulate tabular data. The dataset is stored in a CSV file.

2. **Data Pre-processing**: To ensure the quality of our analysis, rows with missing values are removed, as these rows do not contain the necessary data for sentiment analysis.

3. **Distribution of Ratings**: The distribution of ratings given by customers is explored and provides an overview of how customers generally rate the products.

4. **Sentiment Analysis**: To delve deeper into the customers' sentiments, sentiment analysis on the review text is performed. Sentiment Intensity Analyser (SIA) sentiment analysis tool is used to calculate positive, negative, and neutral sentiment scores for each review.

5. **Analysis of a Random Product**: To understand the sentiment of a specific product, a product is randomly selected from the dataset. The sum of positive, negative, and neutral sentiment scores for this product is calculated to determine the overall sentiment based on the highest score.

## Visualizations

The results are visualized in the analysis using various charts and plots. These visualizations help in better understanding the data and the sentiment analysis results:

1. **Pie Charts**: Pie charts are created to show the distribution of rating scores and the sentiment breakdown of the selected product.

2. **Donut Chart**: A donut chart is used to display the distribution of rating scores in a more visually appealing and informative way.

3. **Sentiment Analysis Chart**: A pie chart is created to represent the sentiment analysis results for the random product. It shows the percentage of positive, negative, and neutral sentiment.

## How to Use

To run this project on your dataset or perform sentiment analysis on Amazon product reviews, you can follow the code and instructions in the repository. Make sure you have the necessary libraries installed and provide the correct file path to your dataset.

Feel free to modify and extend this project to suit your specific requirements and analysis goals.
