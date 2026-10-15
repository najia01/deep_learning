Deep Learning

Exercice 1 : Le Perceptron simple

Coder un neurone artificiel de zéro (sans Keras) pour résoudre un problème de classification binaire (Porte logique NOR).
Un neurone seul trace une frontière linéaire via une somme pondérée et une fonction d'activation. L'entropie croisée accélère la descente de gradient.

Exercice 2 : Réseau multicouche (MLP) sur Iris

Classifier des fleurs en 3 catégories avec Keras.L'importance du train_test_split avant le StandardScaler pour éviter la fuite de données. Utilisation de Softmax pour une classification multi-classes.

Exercices 3 & 4 : CNN sur MNIST & Fashion-MNIST

Reconnaître des images de chiffres (0-9) et de vêtements (28x28 pixels).
Les couches Conv2D extraient les caractéristiques spatiales, MaxPooling2D réduit la taille, Flatten aplatit, et Dropout évite le sur-apprentissage.

Exercice 5 : Pipeline complet sur le Titanic

Prédire la survie d'un passager sur un dataset "sale" comportant du texte et des valeurs manquantes.
Remplacer les valeurs nulles, utiliser get_dummies pour les variables catégorielles, et utiliser l'EarlyStopping pour stopper l'entraînement au moment optimal.

Exercice 6 : Génération de texte (NLP) avec LSTM (Victor Hugo)

Prédire le mot suivant dans un poème à partir des 3 mots précédents.
Utilisation d'un Tokenizer et de l'Embedding pour donner du sens aux mots. Supériorité de la mémoire du LSTM sur le SimpleRNN. Contrôle de la génération par la temperature.
