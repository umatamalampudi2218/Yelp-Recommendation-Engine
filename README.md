### README

## Voice of the Customer: Sentiment Analysis using Yelp Data

### Description
This project involves developing a scalable sentiment analysis system using Yelp review data to understand customer sentiment toward businesses. The analysis includes cloud setup, data cleaning, data preprocessing, exploratory data analysis, and sentiment classification using machine learning models like Logistic Regression and Naive Bayes.

### Prerequisites
Before you begin, ensure you have met the following requirements:
- **Python 3.7** or higher installed
- **Jupyter Notebook**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, **Scikit-learn**, **NLTK**, **Spark** libraries installed

### Installation and Setup
To install and set up the project, follow these steps:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/voice-of-the-customer.git
   cd voice-of-the-customer
   ```

2. **Set up the Python Environment:**
   Create a virtual environment and install the required libraries:
   ```sh
   python -m venv env
   source env/bin/activate
   pip install -r requirements.txt
   ```

3. **Open the Jupyter Notebooks:**
   Open and run the following notebooks in Jupyter:
   - `DF_1mil_ML.ipynb`
   - `DF_Sentiment_Wordcloud.ipynb`
   - `Scalable_Final_Project_EDA.ipynb`

### Using the Project
Once the Jupyter Notebooks are open, you can run the cells to execute the following steps:

1. **Cloud Setup:**
   - Establish the cloud infrastructure using the GSU cluster to ensure data accessibility and integrity.
   - Transfer data files to HDFS and verify their accessibility.

2. **Data Cleaning:**
   - Downsized the dataset to 3 million reviews using cluster computing.
   - Eliminated rows with null values and standardized column data types.

3. **Data Preprocessing:**
   - Used RDDs to categorize users into 'generous,' 'normal,' and 'picky' based on rating behavior.
   - Built an NLP pipeline for sentiment analysis, including tokenization, stop word removal, feature hashing, and IDF weighting.

4. **Exploratory Data Analysis:**
   - Analyzed star rating distributions and identified unique users.
   - Visualized user sentiment patterns using word clouds and other graphical representations.

5. **Model Development:**
   - Trained Logistic Regression and Naive Bayes models on the preprocessed dataset.
   - Evaluated model performance using accuracy and F1-score.
  

Engineered a robust data processing pipeline on GCP Cluster using Apache Spark and Resilient Distributed Datasets (RDDs) to preprocess and analyze 3 million Yelp reviews, employing word cloud visualizations to highlight key sentiment terms effectively.
Spearheaded the data cleaning initiative, utilizing Apache Spark to refine and validate a dataset of 3 million Yelp reviews, focusing on essential variables to enable accurate sentiment analysis.
Developed and optimized Logistic Regression and Naive Bayes models to classify sentiments within Yelp reviews, achieving an accuracy of over 85% with Naive Bayes, demonstrating high efficacy in predictive analytics.
Analyzed and visualized sentiment trends using natural language processing and visual analytics, revealing distinct sentiment patterns across 633,771 unique Yelp users, thereby enriching the dataset with detailed sentiment metrics.


### Results Analysis and Interpretation
- **Initial Model:** Logistic Regression achieved high interpretability but lower accuracy compared to Naive Bayes.
- **Improved Model:** Naive Bayes showed superior accuracy and F1-score, making it the more effective model for sentiment classification.

### Key Findings
- **Positive Sentiment Dominance:** Generous reviewers predominantly expressed positive sentiments.
- **Balanced Sentiment:** Normal reviewers showed a balanced sentiment distribution.
- **Critical Reviews:** Picky reviewers displayed significant negative sentiments but also some positive feedback.

### Contributing to the Project
To contribute, follow these steps:
1. **Fork the repository.**
2. **Create a branch:**
   ```sh
   git checkout -b <branch_name>
   ```
3. **Make your changes and commit them:**
   ```sh
   git commit -m '<commit_message>'
   ```
4. **Push to the original branch:**
   ```sh
   git push origin <project_name>/<location>
   ```
5. **Create a pull request.**

### License
This project is licensed under the @2023 Surya Kiran Varma Vegesna.

### Contact
If you have any questions or want to contribute, please email us at umatamalampudi26@gmail.com


