Caractéristiques du dataset :


- il faut importer les 3 fichiers en utilisant les modules appropriés 


- il faut regarder les trois fichiers, identifier si il y a des valeurs manquante ( utiliser .info() par exemple)


- si il y a des valeurs manquantes , selon vos analyses effectuées, il faudra faire un choix : les retirer, les remplacer.... pour aller plus loin : https://moncoachdata.com/blog/nettoyage-de-donnees-python/


- Valeurs aberrantes : des transactions de test sont présentes dans la table transactions il faut les identifier et faites votre choix ( les supprimer, les remplacer?...)


- La fiche produit manque pour le produit id = 0_2245 vendu 103 fois, que pensez vous?
Une série d’indicateurs statistiques de tendances centrales et dispersions doivent être calculés sur les différentes variables quantitatives disponibles. On peut également envisager de calculer par exemple ces indicateurs par catégorie, tranche d’âge, etc.
Dans tous les cas, l’évolution du chiffre d’affaires dans le temps est indispensable,

Concernant les produits, un simple groupby avec des filtres adaptés devrait permettre de couvrir les différents aspects. Une courbe de Lorenz pourrait d’ailleurs être intéressante pour faire ressortir l’effet Pareto.( c'est en bonus pour les courageux)
Idem pour les clients. Ceci étant, une analyse de la répartition des âges est ici pertinente.
Réaliser une analyse univariée et bivariée pour interpréter des données :  je regarderai :
Genre du client et catégorie de produits achetés.
Âge des clients et montant total des achats.
Âge des clients et fréquence d’achat.
Âge des clients et panier moyen.
Âge des clients et catégorie de produits achetés.
