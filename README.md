# Reddit Score Predictor Project

## Overview
This project aims to predict the popularity of posts on the r/askscience subreddit by analyzing various attributes that contribute to their success. The goal is to identify key factors that resonate with the subreddit community and guide content creators in crafting engaging posts.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Loading](#data-loading)
3. [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Feature Engineering](#feature-engineering)
6. [Model Preparation](#model-preparation)
7. [Predictive Modeling](#predictive-modeling)
8. [Insights and Conclusion](#insights-and-conclusion)

### Dataset Overview
The dataset (`askscience_data.csv`) comprises posts from the r/askscience subreddit, known for scientific discussions and expert contributions. Key features of each post include:
- `title`: The title of the post.
- `body`: The main text content of the post.
- `tag`: The category or field of science the post pertains to.
- `datetime`: The date and time the post was submitted.
- `author`: The username of the post's creator.
- `score`: The net number of upvotes minus downvotes the post has received. A higher score indicates that a post has received more upvotes than downvotes, reflecting overall community approval.
- `upvote_ratio`: The ratio of upvotes to the total number of votes (upvotes plus downvotes). This ratio, expressed as a percentage, shows the proportion of viewers who liked the post. A higher upvote ratio indicates a higher consensus among voters in favor of the post.
- `url`: The direct link to the Reddit post. This URL can be used to access the post directly and may play a role in how the post is shared and viewed externally, potentially affecting its visibility and popularity.

### NLP and Deep Learning Techniques Employed

This project illustrates the practical application of NLP and machine learning techniques through a structured approach to data analysis and model building. Key aspects demonstrated include:

- **Data Preprocessing and Management**: The project begins with meticulous data cleaning and preparation, setting a strong foundation for subsequent analysis. This step is crucial for any data science project and is handled with attention to detail here.

- **Exploratory Data Analysis (EDA)**: Through comprehensive EDA, this work provides insights into the data's characteristics and the relationships between different variables. This phase is essential for understanding the dataset and informing the direction of further analysis.

- **Thoughtful Feature Engineering**: The transformation of raw text into informative features showcases a careful consideration of how textual data can be leveraged to predict outcomes. This includes the innovative use of text embeddings and phrase mining to enhance model input.

- **Model Development and Validation**: The analysis begins with a RandomForestRegressor as the baseline model to understand feature impacts and model performance. It further explores an XGBoost model for its gradient boosting capabilities and a simplified Neural Network model to capture non-linear interactions and complex patterns. This diverse approach to modeling facilitates a robust evaluation of different algorithms, illustrating the strengths and trade-offs of each.

- **Insights and Practical Recommendations**: The conclusion offers actionable insights and detailed recommendations, like enhanced text representation and advanced modeling techniques, aimed at optimizing submissions to the subreddit. This section connects the findings directly with practical applications, underscoring the relevance of sophisticated NLP techniques in real-world settings.


For a detailed walkthrough of the analysis and methodologies, explore the [Jupyter Notebook](https://github.com/towardsNLP/Reddit-Score-Predictor/blob/main/RedditScorePredictor.ipynb) included in this repository.

