# NLP Analysis of Commencement Speeches
### Semester IV Project | NMIMS BSc Applied Mathematical Computing, November 2024

**Author:** Tanushri Shetty  

---

## Objective
Comprehensive NLP analysis of 322 US university commencement speeches 
to uncover thematic trends, sentiment patterns, and emotional content.

---

## Notebooks (run in order)

| # | Notebook | What it does |
|---|----------|-------------|
| 01 | `preprocessing` | DTM, lemmatization, stop word removal |
| 02 | `eda` | Word frequency, word clouds, speaker/university stats |
| 03 | `topic_modelling` | TF-IDF + NMF → 7 topics, trends by year/region/profession |
| 04 | `sentiment_emotion` | VADER polarity, TextBlob subjectivity, NRC emotion lexicon |

---

## Key Findings

- **Top topics:** Family & Advice (24.8%), Ambition (18.6%), Nation & Freedom (15.8%)
- **Regional gap:** Zero "Women's Voice" speeches in the conservative Central US region
- **Tech/Business speakers** talk almost exclusively about Ambition
- **Sentiment:** All speeches skew positive; polarity dips in the middle then rises at the end
- **Top emotions:** Positive, Trust, Anticipation dominate across all speeches

---

## Methods
TF-IDF · NMF Topic Modelling · VADER Sentiment Analysis · 
TextBlob Subjectivity · NRC Emotion Lexicon

---

## Tech Stack
`pandas` · `numpy` · `nltk` · `scikit-learn` · `gensim` · `vaderSentiment` · `textblob`

---

## How to Run

```bash
git clone https://github.com/YOUR_USERNAME/nlp-commencement-speeches.git
pip install pandas numpy nltk scikit-learn gensim textblob wordcloud matplotlib seaborn
# See data/README.md for data file setup
# Run notebooks in order: 01 → 02 → 03 → 04
```

---
