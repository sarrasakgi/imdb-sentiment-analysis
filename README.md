# Analyse de Sentiments — IMDB

Comparaison de trois familles d'approches NLP pour la classification
binaire de sentiments sur le dataset IMDB (50 000 critiques de films).

## Notebooks

| Notebook | Contenu |
|---|---|
| `01_classical_bilstm.ipynb` | TF-IDF + classifieurs linéaires + Bi-LSTM |
| `02_transformers.ipynb` | Fine-tuning DistilBERT, BERT-base, RoBERTa |

## Données

Le dataset IMDB est disponible sur Kaggle :
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

→ Télécharger `IMDB Dataset.csv` et le placer à la racine avant d'exécuter les notebooks.

## Rapport

Voir `rapport/rapport_final.pdf`

## Environnement
```bash
pip install numpy pandas scikit-learn tensorflow torch transformers nltk matplotlib
```