# Bank Churn Prediction

## Description

Le jeu de données Bank Customer Churn est fréquemment utilisé pour prédire l'attrition des clients dans le secteur bancaire. Ce projet vise à développer un modèle capable de prédire si un client quittera la banque ou continuera d'y être fidèle. Les jeux de données contiennent des informations détaillées sur les clients, incluant leurs caractéristiques démographiques, comportementales, ainsi que des données sur leurs interactions avec la banque.

L'objectif principal du projet est de prédire la variable cible Churn, qui indique si un client a quitté la banque ou non, en utilisant différentes techniques de modélisation et d'optimisation. L'accent est mis sur l'optimisation de la performance des modèles en maximisant l'AUC (Area Under the Curve). 

## Prérequis

Pour utiliser ce projet, vous devez d'abord créer un environnement virtuel et installer les packages répertoriés dans le fichier `requirements.txt`.

## Installation

1. Cloner le dépôt sur votre machine :
   ```bash
   git clone https://github.com/salmabens/bank-churn-prediction.git
   cd bank-churn-prediction
   ```

2. Créer un environnement virtuel :
      *Sous Windows :
         ```bash
         python -m venv env
         ```
      *Sous macOS/Linux :
         ```bash
         python3 -m venv env
         ```
3. Activer l'environnement virtuel :

*Sous Windows :
   ```bash
   .\env\Scripts\activate
   ```
*Sous macOS/Linux :
   ```bash
   source env/bin/activate
   ```

4. Installer les dépendances avec pip :
   ```bash
   pip install -r requirements.txt
   ```

## Structure des fichiers
``` 
/Data             # Contient les jeux de données
    ├── train.csv  # Jeu de données d'entraînement
    └── test.csv   # Jeu de données de test
/Modèles_finaux   # Contient les deux modèles finaux
    ├── CatBoost_predictions.csv  # Modèle le plus performant
    └── XGboost_predictions.csv   # Second modèle le plus performant
/Notebook.ipynb      # Contient le notebook principal
/Présentation.pdf    # Contient le support de présentation
/README.md           # Ce fichier
/Requirements.txt    # Liste des dépendances Python
```
## Contributeurs

- **Salma BENMOUSSA**
- **Charlotte CEGARRA**

Ce projet a été développé dans le cadre du Master MOSEF, à l'université Paris 1 Panthéon Sorbonne.

## 📩 Contact

N'hésitez pas à nous contacter pour toute question :

- salmabenmoussa103@gmail.com 
- charlottecegarrapro@gmail.com
