# 📘 NLP Assignments & Text Representation Project

This repository contains my complete NLP (Natural Language Processing) assignments, notebooks, and text-processing experiments.  
It includes preprocessing, tokenization, text representation techniques, TF-IDF, n-grams, and more — all implemented from scratch and with Scikit-Learn.

> ⚠️ **Note:** The dataset `cleaned_imdb_dataset.csv` is **not included** because GitHub does not allow files larger than 100 MB.

---

## 📂 Project Structure
NLP/
│
├── Assignments.ipynb # Full assignment solutions

├── Text Representation.ipynb # Bag of Words, Bi-grams, TF-IDF, etc.

├── .gitignore # Ignored files (venv, checkpoints, data, etc.)

└── README.md # Project documentation

---


---

## 🧠 What’s Inside

### ✔ **Text Preprocessing**
- Lowercasing  
- Removing special characters  
- Removing numbers  
- Tokenization  
- Stopword removal  
- Lemmatization  

### ✔ **Text Representation Techniques**
- Bag of Words (BoW)  
- Bi-grams  
- Tri-grams  
- TF-IDF  
- Vocabulary generation  
- One-hot encoding  
- Counting unique words in corpus  

### ✔ **Exploratory Analysis**
- Vocabulary dimensionality  
- Sparsity of matrix  
- Impact of n-gram size  
- IDF score interpretation  

---

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebook**
- **NLTK**
- **Scikit-Learn**
- **Pandas**
- **NumPy**
- **Regex**

---

## 📊 Results & Observations

### 📌 **N-Gram Dimensionality**
- Increasing n-gram size increases vocabulary size.
- Tri-grams produce the largest feature space.
- Higher n-grams capture more context but require more memory.

### 📌 **TF-IDF**
- Rare but meaningful words get higher importance.
- Frequent words (even non-stopwords) get lower scores.

---

correct it 

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/radha35/NLP.git

2. Create virtual environment (optional):
   ```bash
   python -m venv .venv

3. Install dependencies:
```bash
pip install -r requirements.txt

4. Open notebooks:
```bash
jupyter notebook





