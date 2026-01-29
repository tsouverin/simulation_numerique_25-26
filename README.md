# Simulation numérique ; 2025-2026

## **Objectifs Pédagogiques**

Ce projet pédagogique vise à introduire des concepts de **simulation numérique** en **python** appliqués à la **modélisation** des concepts physiques connus. A partir de **lois astrophysiques** et de **mécanique céleste**, vous allez générer votre propre **système stellaire** !

Les supports de TPs sont sous la forme de Jupyter Notebook, avec un par séance contenant :

- Une introduction aux **outils python** avec exercices simples
- Une introduction à un **concept physique**
- **Application** des outils à ce concept physique

Aucun prérequis n'est nécessaire, que ce soit en programmation sous python ou en astrophysique, toutes les notions seront introduites durant les séances !

---

## **Instructions**

### **1. Importer le projet**
Pour récupérer le projet, cliquez sur le bontou vert "<> Code" en haut à droite de cette page, puis télécharger le fichier zip.
Décompressez-le dans le répertoire de votre choix sur votre machine.

### **2. Installer les dépendances**
Ouvrez un terminal, et placez vous dans le répertoire du projet :
```bash
cd ./chemin_vers_projet/simulation_sumerique_25-26
```

Puis installez les dépendances nécessaires avec la commande suivante dans votre terminal:
```bash
python -m pip install -r requirements.txt
```

### **3. Ouvrir Jupyter Notebook.**

## **Avec Anaconda** :
Ouvrez le navigateur Anaconda, et ouvrir Jupyter Notebook.

Si vous avez sauvegardé vos travaux dans un autre disque, par exemple "P:", ouvrez un terminal avec Anaconda Prompte et lancez Jupyter Notebook directement dans ce répertoire en utilisant la commande suivante :
```bash
python -m notebook --notebook-dir="P:/chemin_vers_projet/simulation_numerique_25-26"
```

## **Sans Anaconda** :

Pour démarrer l'environnement Jupyter Notebook, exécutez la commande suivante dans le répertoire du projet :
```bash
python -m notebook
```
Cela ouvrira une interface dans votre navigateur où vous pourrez accéder aux fichiers `.ipynb`.

Si vous avez sauvegardé vos travaux dans un autre disque, par exemple "P:", vous pouvez lancer Jupyter Notebook directement dans ce répertoire en utilisant la commande suivante :
```bash
python -m notebook --notebook-dir="P:/chemin_vers_projet/Maths6_ModNum_25-26"
```

### **4. Avant chaque séance**
Téléchargez le nouveau fichier zip du projet depuis GitHub et décompressez-le. Ce nouveau dossier contiendra les nouvelles séances et corrections à jour.

:exclamation: Assurez-vous de sauvegarder vos travaux si vous remplacer les anciens fichiers par des nouveaux.

<!-- ### **4. Avant chaque séance**
En vous placant dans le dossier correspondant au projet, utilisez la commande suivante pour télécharger les dernières modifications, et être sûrs d'avoir toutes les séances et corrections à jour :
```bash
cd ./Maths6_ModNum_25-26
git pull
``` -->

---

## **Organisation des fichiers**

Le jupyter notebook de la séance 1 est contenus dans le dossier **seance1**. Au fil des séances, les nouveaux dossiers contenant les futurs séances seront uploadé dans le projet, ainsi que les versions corrigées de ces notebooks.

---

## **Prérequis**
- Python 3.8<=x<=3.13 installé sur votre machine
- Bibliothèques Python nécessaires (installées via `requirements.txt`)

---

## **Licence**
Ce projet est distribué sous la licence MIT. Vous êtes libre de l'utiliser, de le modifier et de le partager.
