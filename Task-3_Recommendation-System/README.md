#  Recommendation System (CODSOFT AI Internship – Task 3)

This project implements a **Hybrid Recommendation System** that combines  
**Content-Based Filtering** and **Collaborative Filtering** techniques.

It is developed as part of the **CODSOFT Artificial Intelligence Internship** and executed using **Google Colab**.



##  Internship Details

- **Internship Domain:** Artificial Intelligence  
- **Organization:** CODSOFT  
- **Task Number:** Task 4  
- **Task Name:** Recommendation System  
- **Platform Used:** Google Colab  



##  Task Description

Create a recommendation system that suggests movies to users based on:
- Movie content (genres)
- User preferences and ratings

The system uses:
- **Content-Based Filtering** (movie similarity)
- **Collaborative Filtering** (user behavior)
- **Hybrid approach** combining both methods



##  Technologies Used

- Python  
- Pandas  
- Scikit-learn  
- CountVectorizer  
- Cosine Similarity  
- Google Colab  



##  How the System Works

### 1️ Content-Based Filtering
- Uses movie genres
- Converts text genres into vectors using `CountVectorizer`
- Calculates similarity using **Cosine Similarity**
- Recommends movies similar to the selected movie

### 2️ Collaborative Filtering
- Uses user–movie ratings
- Finds movies liked by other users
- Recommends unseen movies to the target user

### 3️ Hybrid Recommendation
- Combines results from both methods
- Removes duplicates
- Produces final recommendations



## ▶️ How to Run 

1. Open **Google Colab**
2. Create a new notebook
3. Install required libraries (if not available):
```python
!pip install pandas scikit-learn
