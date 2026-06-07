# TP_Reseau_De_Neurones_TP1_Rick

TP – Introduction aux réseaux de neurones : MLP sur données tabulaires et images
Objectif
L’objectif de ce TP est d’implémenter des réseaux de neurones multicouches (MLP) sur les mêmes datasets utilisés dans le cours d’algorithmes classiques, afin de :

comparer les performances avec les modèles classiques
comprendre l’impact des hyperparamètres
analyser les comportements d’apprentissage (overfitting / underfitting)
identifier les limites des MLP
Travail demandé
Vous devez construire trois modèles MLP :

Modèle 1 — Régression
Utiliser le dataset de régression du module précédent et entraîner un MLP pour prédire la variable cible.

Modèle 2 — Classification tabulaire
Utiliser le dataset de classification et entraîner un MLP pour prédire la classe.

Modèle 3 — Classification MNIST
Construire un MLP pour classifier les images MNIST (flattened input).



Pour chaque modèle, votre notebook doit inclure :
1 — Préparation des données
Train / validation / test split
Normalisation des features
Encodage si nécessaire
2 — Architecture du modèle
Préciser :

nombre de couches
nombre de neurones
fonctions d’activation
loss function
optimiseur
learning rate
batch size
Justifier brièvement vos choix.



3 — Entraînement
Tracer :

training loss
validation loss
métriques pertinentes
4 — Évaluation
Classification :
accuracy
precision
recall
F1
confusion matrix
ROC curve
Régression :
MAE
RMSE
R²
5 — Analyse critique (important)
Pour chaque modèle :

Répondre brièvement :

Le modèle overfit-il ? Pourquoi ?
Le modèle underfit-il ?
Quelle modification améliorerait les performances ?
Expérimentation obligatoire
Tester au moins deux variantes du modèle :

Exemples :

profondeur du réseau
nombre de neurones
learning rate
dropout
activation
Comparer les résultats.



Questions finales
Répondre en quelques lignes :

Dans quels cas le MLP a-t-il mieux performé que les modèles classiques ?
Dans quels cas les modèles classiques restent-ils meilleurs ?
Pourquoi le MLP est-il moins performant que les CNN sur MNIST ?
Livrable
Un notebook structuré contenant :

code exécutable
graphiques
commentaires courts
réponses aux questions 
