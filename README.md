📊 Analyse Statistique – Santé & Dataset MPG
📌 Contexte du projet

Dans ce projet, j’interviens en tant que Data Analyst junior afin d’explorer et d’analyser des données réelles.

L’objectif principal est de :

Comprendre les concepts statistiques
Les appliquer sur des datasets réels
Produire des analyses fiables et interprétables

Le projet est divisé en deux cas d’usage :

🏥 Analyse de données de santé publique
🚗 Analyse de données automobiles (dataset MPG)
🎯 Objectifs pédagogiques

À l’issue de ce projet, j’ai été capable de :

Définir et expliquer les concepts statistiques clés
Distinguer variables discrètes et continues
Réaliser des analyses descriptives et visuelles
Identifier et interpréter les valeurs aberrantes
Mesurer les relations entre variables (corrélation, tests)
Appliquer des tests d’hypothèses
Relier la théorie statistique à un contexte métier
🧠 Phase 1 – Compréhension & Documentation

Étude des notions statistiques fondamentales :

Statistiques descriptives :
Moyenne, médiane, variance, écart-type
Histogramme, boxplot
Population vs Échantillon
Lois de probabilité :
Bernoulli, Binomiale, Poisson, Normale, Student, Chi²
Théorème Central Limite (TCL)
Échantillonnage & estimation
Tests d’hypothèses :
H0 / H1
p-value
Décision statistique
🏥 Phase 2 – Analyse du dataset de santé
🔍 Analyse des variables
Identification des variables discrètes et continues
Analyse de la variable Country
Analyse de Spending_USD
Analyse de Life_Expectancy
📈 Visualisations
Histogrammes
Boxplots
Évolution dans le temps
🔗 Corrélation
Étude de la relation entre :
Dépenses de santé (Spending_USD)
Espérance de vie (Life_Expectancy)
Calcul de la corrélation de Pearson :
from scipy.stats import pearsonr
corr, p_value = pearsonr(x, y)
✅ Résultat principal
Corrélation positive (~0.62)
p-value < 0.05 → relation statistiquement significative

👉 Conclusion :
Une augmentation des dépenses de santé est associée à une augmentation de l’espérance de vie.

⚠️ Analyse des valeurs aberrantes
Détection via boxplot
Interprétation des anomalies
🧪 Bonus – Test d’hypothèse

Hypothèse testée :

L’espérance de vie augmente de 0.3 an par an aux États-Unis depuis 1970

Utilisation de .diff() pour les variations
Test avec α = 0.02
Interprétation via p-value
🚗 Phase 3 – Analyse du dataset MPG
🔍 Analyse exploratoire
Variables discrètes vs continues
Étude de :
mpg
cylinders
origin
📊 Analyses réalisées
Moyenne et interprétation de mpg
Visualisations (histogramme, scatter plot)
Relation entre :
mpg et horsepower
cylinders et année
cylinders et origine
📈 Analyse temporelle
Évolution du poids des voitures (1970 → 1982)
Impact de l’année sur les performances
🚀 Résultats clés
Relation négative entre horsepower et mpg
Diminution du poids des voitures dans le temps
Différences selon l’origine (USA vs Europe vs Japon)
🛠️ Technologies utilisées
Python 🐍
Pandas
NumPy
Matplotlib / Seaborn
SciPy
📌 Conclusion générale

Ce projet m’a permis de :

Passer de la théorie à la pratique
Manipuler des données réelles
Comprendre les relations entre variables
Produire des analyses exploitables