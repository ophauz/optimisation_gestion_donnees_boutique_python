## Optimisation de la gestion des données d'une boutique avec Python

![p5_1](https://user-images.githubusercontent.com/87067133/217518705-671a3790-aa3c-4980-85cf-1888e6166bef.png)

### Contexte : 
 
L'entreprise utilise un ERP non relié au site de vente en ligne. Les données sont éparses, la gestion des stocks complexe et la visibilité en terme d’analyse des ventes sur le Net réduite, car peu de personnes ont accès au back-office. En attendant une solution pérenne, un rapprochement manuel entre les 2 bases de données est demandé.

### Missions :

##### - Data wrangling : Repprochement de l'export de l’ERP (références produit, prix de vente, état de stock) et de l'export de l’outil de CMS contenant les informations des produits commercialisés en ligne (nom, description, nombre de ventes, etc.)

Code et dataframe obtenu visibles sur le [notebook](ophauz_optimisation_gestion_donnees_boutique_python_notebook.ipynb) du projet.

##### - Analyse : obtention du chiffre d’affaires par produit, ainsi que le total du chiffre d’affaires réalisé en ligne

![p5_2](https://user-images.githubusercontent.com/87067133/217580610-997adf35-7cc5-471e-9b7e-d12108e32831.png)
![p5_3](https://user-images.githubusercontent.com/87067133/219487663-0a2fa009-aa58-4b86-b8c8-89b4b9a712e8.png)


##### - Data cleaning : Recherche d'éventuelles erreurs de saisie dans certains prix des produits

![p5_4](https://user-images.githubusercontent.com/87067133/219487926-0916cf02-d11c-49fb-99e7-156b509b8ed0.png)
![p5_5](https://user-images.githubusercontent.com/87067133/217580690-15c722b8-a71f-4ffa-acee-a56b6f6d8dc6.png)


##### Environnement technique : Jupyter Notebook, Python, Pandas, NumPy, SciPy, Seaborn
