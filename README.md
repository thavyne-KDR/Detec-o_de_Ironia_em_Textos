## 🤖 Detector de Ironia em Textos

> Classifique textos em português como **irônicos** ou **não irônicos** usando Machine Learning.

---

## 🏆 Desafio

- Detectar ironia em textos do português.
- Competição Kaggle: acurácia balanceada.

---

## 📊 Exemplo de Submissão

```
ID,LABEL
2,0
5,1
6,0
```

- `1` = Irônico
- `0` = Não irônico

---

## ⚙️ Tecnologias

### Ferramentas e Ambientes

- 🐍 **Python 3**
- 🔥 **PyTorch**
- 🤗 **Hugging Face Transformers** (BERTimbau)
- 📊 **Scikit-learn**
- 🐼 **Pandas**
- 🔢 **NumPy**
- 🟦 **Google Colab**
- 🧠 **TensorFlow + Keras**

---

### Abordagens e Algoritmos

**1️⃣ Modelos Clássicos com TF-IDF** - TF-IDF (TfidfVectorizer) - Regressão Logística - Support Vector Machine (LinearSVC) - Naive Bayes (MultinomialNB) - Random Forest - Gradient Boosting - AdaBoost

**2️⃣ Modelos com Embeddings de Sentença** - Sentence-Transformers (paraphrase-MiniLM-L3-v2) - Algoritmos clássicos sobre embeddings

**3️⃣ Modelos de Deep Learning (CNN)** - TensorFlow + Keras - Camada de Embedding - Conv1D - GlobalMaxPooling1D - Dense, Dropout

---

### Técnicas e Estratégias

- Engenharia de Características (ex: text_length, punctuation_count)
- Tunagem de Hiperparâmetros (GridSearchCV)
- Validação Cruzada (StratifiedKFold, cross_val_score)
- Ensemble de Modelos (VotingClassifier, Ensemble Averaging)
- Early Stopping
- Aceleração por GPU (cuda:0)
- Métrica customizada: balanced_accuracy

---

## 🚀 Como Usar

1. Instale dependências
2. Treine/teste o modelo
3. Gere o arquivo de submissão

---

## 🔗 Referência

[Kaggle - Detecção de Ironia](https://www.kaggle.com/competitions/classificacao-de-ironia)

---




