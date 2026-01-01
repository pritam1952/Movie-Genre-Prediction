# Movie Genre Prediction 🎬

**Project ID:** #CC69848  
**Internship Domain:** Data Science Intern  
**Project Level:** Intermediate  

## Project Overview
This project predicts the **genre of a movie** based on its plot summary using **Natural Language Processing (NLP)** techniques. It is a **text classification** problem where movie descriptions are converted into numerical features and used to train a machine learning model.

**Technologies Used:**  
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- NLTK (Text preprocessing)  
- Scikit-learn (TF-IDF, Naive Bayes)  
- Pickle (Model saving)

---

## Dataset
The dataset contains information about movies including:  

- `Title` – Name of the movie  
- `Description` – Plot summary of the movie  
- `Genre` – Movie genre (target variable)  

**Note:** The dataset is not uploaded here due to size constraints. You can download a similar dataset from [Kaggle](https://www.kaggle.com/datasets/PromptCloudHQ/imdb-data).

---

## Project Steps

### 1. Data Cleaning
- Removed missing values in `Description` and `Genre`.  
- Renamed columns for easier access.

### 2. NLP Preprocessing
- Converted text to lowercase  
- Removed punctuation, numbers, and stopwords  
- Tokenized and lemmatized text  

### 3. Exploratory Data Analysis (EDA)
- Visualized genre distribution using **countplots**  
- Generated **WordClouds** to find most frequent words in plots  

### 4. Feature Extraction
- Converted text into numerical features using **TF-IDF Vectorizer**  

### 5. Model Training
- Split data into **training (80%)** and **testing (20%)**  
- Trained **Multinomial Naive Bayes classifier**  

### 6. Model Evaluation
- Accuracy, precision, recall, F1-score  
- Confusion matrix visualization  

### 7. Predictions
- Created a function to predict genre for any new movie plot  

---

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/YourUsername/Movie-Genre-Prediction.git
