# 🏥 Prematurity – Prédiction de l'Accouchement Prématuré  

## 📌 Description  
**Prematurity** est une application d'aide à la décision développée avec **Streamlit** qui permet de prédire le risque d'accouchement prématuré chez les femmes déjà en travail prématuré.  
L'application utilise un modèle de **Machine Learning** entraîné sur un jeu de données contenant **13 variables prénatales** pour assister les professionnels de santé dans leurs prises de décision.  

## 📊 Données  
Le dataset utilisé dans ce projet comprend **390 observations** et **13 variables prédictives** :  

| 🏷️ Variable  | 📖 Description |
|-------------|--------------|
| **GEST** | Âge gestationnel en semaines à l'entrée dans l'étude |
| **DILATE** | Dilatation du col en cm |
| **EFFACE** | Effacement du col (en %) |
| **CONSIS** | Consistance du col (1 = mou, 2 = moyen, 3 = ferme) |
| **CONTR** | Présence (1) ou absence (2) de contractions |
| **MEMBRAN** | Rupture des membranes (1 = oui, 2 = non, 3 = incertain) |
| **AGE** | Âge de la patiente |
| **STRAT** | Période de la grossesse |
| **GRAVID** | Nombre de grossesses antérieures (y compris en cours) |
| **PARIT** | Nombre de grossesses à terme antérieures |
| **DIAB** | Présence (1) ou absence (2) de diabète, ou valeur manquante (9) |
| **BEBAGE** | Âge gestationnel du bébé à la naissance (en jours) |
| **TRANSF** | Transfert vers un hôpital en soins spécialisés (1 = oui, 2 = non) |
| **GEMEL** | Grossesse simple (1) ou multiple (2) |

🔮 **Variable cible :** `PREMATURE` (0 = accouchement à terme, 1 = accouchement prématuré)

## 🚀 Fonctionnalités  
- **Exploration des données** : affichage et visualisation des variables clés  
- **Prétraitement des données** : gestion des valeurs manquantes, normalisation, encodage  
- **Entraînement et évaluation du modèle** : plusieurs modèles testés, optimisation des hyperparamètres  
- **Interface utilisateur interactive** : formulaire pour entrer les paramètres et obtenir une prédiction  

## 🛠️ Installation et Exécution  
### 1️⃣ Cloner le projet  
```bash
git clone https://github.com/sefdineehmed/prematurity.git
cd prematurity
```

### 2️⃣ Installer les dépendances  
```bash
pip install -r requirements.txt
```

### 3️⃣ Lancer l'application  
```bash
streamlit run app.py
```

## 📂 Structure du projet  
```
prematurity/
│── data/               # Dossier contenant les données (à ne pas publier)
│── models/             # Modèles entraînés sauvegardés
│── notebooks/          # Expérimentations en Jupyter Notebook
│── app.py              # Code principal de l'application Streamlit
│── requirements.txt    # Dépendances du projet
│── README.md           # Documentation du projet
└── .gitignore          # Fichiers à ignorer par Git
```

## 📈 Modèle de Machine Learning  
Le modèle utilisé est basé sur un **Random Forest Classifier** (modifiable selon les performances).  

## 🎯 Objectif  
Ce projet vise à fournir un **outil d’aide à la décision** pour les professionnels de santé, permettant d’anticiper les accouchements prématurés et d’améliorer la prise en charge des patientes.

## 🧑‍💻 Contact  
📩 **Email** : ahmed.sefdine@uadb.edu.sn  
🔗 **LinkedIn** : [sefdineehmed](https://linkedin.com/in/sefdineahmed) 
