# BPR vs iALS: Impact of Interaction Nature on Recommender System Quality

Master's thesis research at Ulyanovsk State University, 2026.

## Description

Comparison of matrix factorization algorithms **BPR** (Bayesian Personalized 
Ranking) and **iALS** (Implicit Alternating Least Squares) trained on organic, 
algorithmic, and mixed subsets of the **Yambda-50M** dataset (Yandex Music).

The key research question: how does the nature of implicit feedback 
(organic vs. algorithmically generated interactions) affect recommendation 
quality?

## Repository Structure

| File | Description |
|------|-------------|
| `preprocessing.ipynb` | Data preprocessing and formation of three subsets |
| `bpr_training_metrics.ipynb` | BPR model training and evaluation |
| `ials_training_metrics.ipynb` | iALS model training and evaluation |
| `analytics.ipynb` | Correlation analysis and metric interpretation |
| `visualization.ipynb` | Charts and visualizations |
| `bpr_training.html` | BPR training log (HTML export) |
| `final_results.csv` | Final metric results for all experiments |
| `yambda_characteristics.csv` | Dataset subset characteristics |

## Evaluated Metrics

- Recall@K
- NDCG@K  
- Coverage@K
- Novelty@K

## Dataset

Yambda-50M — open industrial dataset by Yandex Music.  
[arXiv:2505.22238](https://arxiv.org/abs/2505.22238)

## Libraries

- [RecBole](https://recbole.io/) — BPR implementation
- [Implicit](https://github.com/benfred/implicit) — iALS implementation

## Author

Akhmiatzanova Anna Ruslanovna  
Scientific supervisor: Butov Alexander Alexandrovich  
Ulyanovsk State University, 2026
