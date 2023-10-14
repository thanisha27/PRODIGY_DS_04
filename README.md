# PRODIGY_DS_04
Task: Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands.

Steps:

 It uses several libraries, including Pandas, NumPy, Seaborn, Matplotlib, and scikit-learn for data analysis and visualization. Here's a breakdown of what each part of the code does:
 - Data Loading
   
 - Data Renaming :The code renames specific columns in the training and validation datasets to more meaningful names, presumably for better clarity.

- Data Exploration (EDA):The code performs various EDA tasks to understand the data, including checking data shapes, data info, and summary statistics.

- Sentiment Analysis Visualization :It creates various visualizations to analyze the sentiment distribution in the data, such as pie charts and bar plots. The sentiment categories used are "Positive," "Negative," "Neutral," and "Irrelevant."

- Data Cleaning: The code checks for missing values and duplicate rows in the training and validation datasets. It drops duplicate rows and rows with missing text data.

- Additional Sentiment Analysis Visualization :The code creates more visualizations to analyze sentiment distribution in the data, such as bar plots, histograms, and box plots. These visualizations provide insights into the relationship between sentiment, entity, and message length.

- Word Cloud Generation: Word clouds are generated to visualize the most frequent words in the data. Word clouds are created for the entire dataset and for each sentiment category.

- Text Preprocessing :The code defines a function preprocess_text_simplified for text preprocessing, which involves converting text to lowercase, simple tokenization, and removing special characters and numbers. This simplified preprocessing is applied to the training data, and the most frequent terms are extracted using CountVectorizer.

- Adjusting Labels :The "Irrelevant" sentiment labels are converted to "Neutral" to simplify the sentiment categories.

- TF-IDF Vectorization: (Term Frequency-Inverse Document Frequency)vectorizer to transform the preprocessed text data into numerical features. The TF-IDF vectorization is applied to both the training and validation datasets.

- Word Cloud for Positive Sentiment: The code generates a word cloud specifically for the "Positive" sentiment category in the training data.
  
