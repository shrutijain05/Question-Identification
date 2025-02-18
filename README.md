# Question Identification using Text Vectorization  

## 📌 Project Overview  
This project explores text vectorization techniques to classify whether a given sentence is a question or not.  
We process a dataset of **235,110** text records and implement **TF-IDF, Word2Vec, and Bag of Words** for text transformation, followed by classification modeling.  

---

## 📂 Dataset Information  
- **Records**: 235,110  
- **Columns**:  
  - `sentence` – The text input  
  - `label` – Classification of the sentence (question or non-question)  

## Tech Stack & Libraries  
- **Python** (`pandas`, `numpy`) – Data preprocessing  
- **Gensim, Scikit-learn** – Vectorization and modeling  
- **Google Colab** – Execution

## Methodology  
### 1️⃣ Data Preprocessing  
✅ Text cleaning: Lowercasing, removing special characters  
✅ Tokenization: Splitting sentences into words  
✅ Stopword removal (optional)  

### 2️⃣ Text Vectorization  
🔹 TF-IDF (Term Frequency-Inverse Document Frequency)  
🔹 Word2Vec (Pretrained Gensim models)  
🔹 Bag of Words (Count Vectorizer)  

### 3️⃣ Model Training & Evaluation  
📊 Splitting data into training/testing sets  
📊 Training a classification model  
📊 Evaluating with accuracy, precision, recall, and F1-score

