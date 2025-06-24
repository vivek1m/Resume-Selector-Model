# 🤖 Resume Selector Model

A machine learning tool to classify resumes into industry-relevant categories using NLP and TF‑IDF features.

---

## 🔍 Key Features

- 🧹 Preprocess resumes: clean text, remove stopwords, mask emails/numbers  
- 🪄 Feature extraction: TF‑IDF (unigrams and bigrams)  
- 🔖 Classification: machine learning model to assign resumes to sectors  
- 📈 Evaluate: accuracy metrics & confusion matrix for performance insights

---

## 🛠️ Tech Stack

- Python  
- NLTK & Scikit‑learn  
- Pandas, NumPy  
- Jupyter Notebook demo

---

## 🚀 Setup & Usage

```bash
git clone https://github.com/vivek1m/Resume-Selector-Model.git
cd Resume-Selector-Model

pip install -r requirements.txt
jupyter notebook Resume_Selector.ipynb
```

In the notebook:  
1. Load CSV dataset  
2. Run preprocessing  
3. Train and evaluate the model  
4. View classification results and plots

---

## 🗂️ Dataset

- Input: CSV file with columns: `ID`, `Category` (industry label), `Resume` (text)  
- Resumes are cleaned, masked, vectorized, and categorized.

---

## 📈 Future Enhancements

- Add modern embeddings (Word2Vec, BERT)  
- Export model with `pickle` or `joblib`  
- Build a web API for real-time classification  
