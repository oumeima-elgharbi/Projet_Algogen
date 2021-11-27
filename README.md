# Projet_Algogen

## Projet de Licence 2 Informatique, Université de Lille

Auteurs : Geoffrey LAFOREST, Achraf AZALMAD, Oumeima EL GHARBI.

Date : novembre 2021.

## Les deux archives sur Github

### Archive "doc" qui permet d'avoir la présentation sous forme de page web du projet et du code.
- Commencer par ouvrir le fichier "index.html" pour accéder au sommaire.
- La documentation et le code de chaque classe et fonction se trouve dans les pages web.
- Par exemple : ouvrir "index.html" puis cliquer sur "algogen module". La documentation apparaît et si l'on clique sur "source" le code python apparaît.
- Le page "journal" fait référence au Readme de l'archive algogen.

### Archive "algogen" qui contient le code.
L'archive contient ces documents : 
- un dossier "src" : contient le code en Python
- un dossier "sourcedoc" : contenant des fichier" .rst pour l'affiche web.
- un dossier "data" : contient un Readme décrivant le projet, et un support PowerPoint pour la soutenance du projet dans le contexte de l'UE AP2 de la L2 Informatique.
- un fichier "confy.py"
- un fichier "Makefile"
- un dossier "_templates" : contenant le fichier "layout.html", c’est un squelette décrivant le format des pages HTML que l'on a produit pour la documentation.

## Contexte : 
La présentation du projet se trouve via ce lien : https://www.fil.univ-lille1.fr/~L2S3API/CoursTP/Projets/AlgoGen/index.html

- L'objectif était de programmer une seule version de l’algorithme génétique (présenté via le lien) et utiliser celui-ci pour résoudre les différents problèmes étudiés.
- Pour chacun de ces problèmes étudié, il a fallu définir une classe pour représenter le problème et une classe pour les individus. 

Les classes pythons communes sont "algogen module", "problem_interface module", "individual_interface module".

Les 4 problèmes sont référencés ici : https://www.fil.univ-lille1.fr/~L2S3API/CoursTP/Projets/AlgoGen/problemes.html
- Problème 1 : Calcul de la valeur maximale d’une fonction (module "problem_function module")
- Problème 2 : Recherche d’un message “secret” (module "problem_secret module")
- Problème 3 : Recherche d’un chemin dans un labyrinthe (module "problem_maze module")
- Problème 4 : Traversée d’un terrain hanté (module "problem_haunted module")

Ainsi, après avoir créé trois modules communs, nous solvons chaque problème à l'aide de ces trois modules.

