#  Loan Solvability Analysis (CRISP-DM)

## Description
Ce projet vise à analyser la solvabilité des emprunteurs afin de prédire la probabilité de remboursement d’un prêt.  
Le projet est structuré selon la **méthode CRISP-DM (Cross-Industry Standard Process for Data Mining)**, qui est une approche standard pour les projets de Data Science.

## Méthodologie CRISP-DM

### 1️⃣ Business Understanding
- Objectif : Identifier les clients à risque et améliorer le processus de décision pour l’octroi de prêts.  
- Question clé : Quels clients sont susceptibles de rembourser ou de ne pas rembourser leur prêt ?

### 2️⃣ Data Understanding
- Analyse initiale du dataset comprenant des variables comme :
  - Âge, revenu, score de crédit
  - Historique de remboursement
  - Montant du prêt demandé
- Vérification des valeurs manquantes et des anomalies.

### 3️⃣ Data Preparation
- Nettoyage des données et traitement des valeurs manquantes
- Encodage des variables catégorielles
- Normalisation ou standardisation si nécessaire

### 4️⃣ Modeling
- Création de modèles de Machine Learning pour prédire la solvabilité :
  - **Logistic Regression**
  - **Decision Tree**
  - **Random Forest**  
- Sélection des hyperparamètres et entraînement des modèles

### 5️⃣ Evaluation
- Évaluation des modèles avec :
  - Précision, Recall, F1-score
  - Matrice de confusion
- Comparaison des performances pour choisir le meilleur modèle

### 6️⃣ Deployment (optionnel)
- Le modèle peut être utilisé pour :
  - Générer des scores de risque pour de nouveaux clients
  - Intégrer la prédiction dans un workflow bancaire

## Technologies utilisées
- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Résultats
- Modèle de classification précis pour prédire la solvabilité
- Visualisations des principaux facteurs de risque
- Recommandations stratégiques basées sur les données

## Auteur
Sabrine Krid

## Licence
MIT License
