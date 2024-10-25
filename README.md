# README

## Description
Ce projet comprend trois notebooks Python permettant de générer des fichiers Excel sur le sujet de l'insertion professionnelle des diplômés de 2023. Les notebooks utilisent des fichiers de base de données et de données venant de Sphinx déposés par l'utilisateur dans le dossier `../BDD`. Les résultats sont enregistrés dans des fichiers Excel correspondant à leur thème dans les dossiers `../Forme/Global`, `../Forme/Genre`, et `../Forme/Specialites`. Les packages Python nécessaires pour exécuter ces notebooks sont `xlrd`, `openpyxl`, `numpy`, et `pandas`. Après l'exécution des notebooks, les fichiers Word présents dans les mêmes dossiers que les nouveaux fichiers Excel seront normalement mis à jour avec les chiffres et graphiques à jour. Si nécessaire, les liaisons devront être refaites.

## Prérequis
- Python 3.x
- `xlrd` (pour lire les fichiers Excel)
- `openpyxl` (pour écrire les fichiers Excel)
- `numpy` (pour les opérations numériques)
- `pandas` (pour la manipulation des données)

Vous pouvez installer les dépendances en utilisant pip :

```bash
pip install xlrd openpyxl numpy pandas
```

## Instructions
Étape 1: Déposer les fichiers données
Déposer les fichiers de base de données Cylcades de la promotion étudiée ainsi que le fichier de données venant de SphinxOnline dans le dossier ../BDD.

Étape 2: Exécuter les notebooks

Chaque notebook lira les fichiers de données depuis le dossier ../BDD et générera un nouveau fichier Excel dans le dossier correspondant sous ../Forme.

Étape 3: Vérifier les liaisons dans les fichiers Word

Après avoir exécuté les notebooks, vérifiez les fichiers Word dans les dossiers ../Forme/Global, ../Forme/Genre, et ../Forme/Specialites pour vous assurer que les chiffres et graphiques sont à jour. Si nécessaire, refaites les liaisons.

## Contenu des Notebooks
1. global.ipynb

    Lit les fichiers de données depuis ../BDD.
    Génère un fichier Excel dans ../Forme/Global.

2. genre.ipynb

    Lit les fichiers de données depuis ../BDD.
    Génère un fichier Excel dans ../Forme/Genre.

3. specialites.ipynb

    Lit les fichiers de données depuis ../BDD.
    Génère des fichier Excel dans ../Forme/Specialites.

## Aide
Si vous rencontrez des problèmes ou avez des questions, n'hésitez pas à me contacter à l'adresse frederic.kesselring@univ-lyon2.fr

