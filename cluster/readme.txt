Maitriser l’API de twitter pour l’extraction des tweets
Maitriser la partie NLP (natural language processing) avec NLTK en Python
Appliquer les principes de nettoyage des données
Classer les tweets : regrouper ensemble les tweets qui sont similaires

Mon application joue le rôle d’assistantet, elle effectue un résumé de toutes les informations contenant chaque tweet en classons ces informations sous forme de groupes de sorte à ce qu’on présente à l’utilisateur un seul Tweet de chaque groupe.
Pour cela, on doit procéder les étapes suivantes :
commençant par le prétraitement des tweets :l’objectif est d’éliminer le texte inutile des tweets tels que les #, les noms des utilisateurs, les url, …
Ensuite je effectue le traitement des tweets,Je fais l’analyse du tweet en respectant les différentes étapes du NLP (Natural LanguageProcessing) en utilisant La bibliothèque NLTK.
Terminant par la classification des tweets en Utilisant l’algorithme K-Means pour classer les Tweets en k classes 
,les tweets sont résumées sous formes de groupes de sorte à ce que les Tweets qui sont dans le même groupe soient similaires. Ainsi, l’utilisateur pourra par la suite lire juste un Tweet de chaque groupe.

