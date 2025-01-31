# Sentiment and Topic Analysis of App Store Reviews

## Description

This project analyzes sentiment and topics of **F-Droid and competitor app reviews** using **TextBlob, VADER, GPT-based models, and LDA topic modeling**. The goal is to extract meaningful insights from user feedback, categorize sentiment, and identify common themes using **natural language processing (NLP) techniques**.

## Features

- **Sentiment Analysis:** Uses **TextBlob** and **VADER** to classify app reviews as positive, negative, or neutral.
- **Topic Modeling:** Implements **Latent Dirichlet Allocation (LDA)** to uncover hidden themes in reviews.
- **GPT-based Analysis:** Leverages language models for deeper sentiment understanding.
- **Data Visualization:** Presents insights through **charts and graphs**.

## Technologies Used

- **Python**
- **NLTK**
- **TextBlob**
- **VADER Sentiment Analysis**
- **GPT-based models**
- **Matplotlib**
- **Pandas**
- **NumPy**
- **Google Play Scraper**
- **Scikit-learn**
- **Latent Dirichlet Allocation (LDA)**
- **Num2Words**
- **Google Colab Data Table**

## Installation

```bash
pip install nltk textblob vaderSentiment matplotlib gensim pandas numpy google-play-scraper scikit-learn num2words
```

## Project Tasks

### **Task 1: Gathering Reviews**

- Scrape and save app reviews using **Google Play Scraper**.

### **Task 2: Preprocessing Text**

- Clean text by removing punctuation, special characters, and stopwords.
- Apply lemmatization and normalize numbers.

### **Task 3: Sentiment Analysis**

- Use **TextBlob & VADER** to classify sentiment.
- Compare sentiment scores with **GPT-based models**.

### **Task 4: Topic Modeling using LDA**

- Extract and analyze topics from reviews using **LDA**.
- Identify high-priority reviews for developers.

## Resources Used

- [TextBlob API Documentation](https://textblob.readthedocs.io/en/dev/api_reference.html#textblob.blob.TextBlob.sentiment)
- [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment)
- [Topic Modeling with Gensim](https://www.machinelearningplus.com/nlp/topic-modeling-gensim-python/)
- [TF-IDF & Cosine Similarity Notebook](https://notebook.community/juanshishido/text-classification/notebooks/tfidf-cosine-similarity-stemmed)
- [YouTube: Sentiment Analysis Basics](https://www.youtube.com/watch?v=GVwjR6lkS6Q\&ab_channel=JiFacts)
- [YouTube: Data Science with Pranjal](https://www.youtube.com/watch?v=4GF-Knz9B10\&ab_channel=LearnDataSciencewithPranjal)
- [YouTube: LDA & Topic Modeling](https://www.youtube.com/watch?v=Alu_cCXNS-k\&t=528s\&ab_channel=ASLearning)
- [YouTube: NLP Techniques](https://www.youtube.com/watch?v=ZgyA1Q2ywbM\&ab_channel=YuhaoYang)
- [YouTube: Advanced Text Analysis](https://www.youtube.com/watch?v=DWJYZq_fQ2A\&ab_channel=ScottSullivan)

