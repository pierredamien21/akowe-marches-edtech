# Projet Horizon Akowé – Analyse de l’Attractivité des Marchés EdTech
## Objectif

Ce projet vise à identifier les pays africains les plus susceptibles d’accueillir la plateforme EdTech Akowé, à l’aide d’un indicateur composite appelé Market Attractiveness Score (MAS).

##  Données

Les données proviennent de la Banque mondiale et couvrent des dimensions démographiques, éducatives, numériques et financières, incluant une estimation du TAM connecté.

## Méthodologie

Sélection et normalisation d’indicateurs clés

Construction de quatre sous-scores :
Scale, Momentum, Ability to Pay, Digital Readiness

Calcul du Market Attractiveness Score (MAS)

Segmentation des pays en trois catégories (Tier 1, 2, 3)

## Résultats

L’analyse montre que l’Afrique du Sud et le Nigéria sont les marchés les plus attractifs pour un déploiement à court terme. La réussite du projet dans ces pays nécessite toutefois la mise en place de partenariats locaux et institutionnels.

## Reproduire l'analyse

1. Téléchargez le jeu *Education Statistics* (EdStats) de la Banque mondiale : https://www.kaggle.com/datasets/theworldbank/education-statistics
2. Placez `EdStatsData.csv`, `EdStatsCountry.csv` et `EdStatsSeries.csv` à côté du notebook. `EdStatsData.csv` n'est pas dans ce dépôt, car il est trop volumineux.
3. Le notebook `analyse_attractivite_edtech.ipynb` a été écrit pour Google Colab et lit les fichiers dans `/content/`. En local, remplacez ce chemin par le dossier où se trouvent les fichiers.

```bash
pip install -r requirements.txt
jupyter notebook analyse_attractivite_edtech.ipynb
```

## Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn

