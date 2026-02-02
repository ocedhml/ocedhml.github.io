Analyse stylométrique – Gustave Flaubert

Ce dépôt contient un travail d’analyse stylométrique portant sur le style de Gustave Flaubert,
dans une perspective de comparaison avec plusieurs auteurs du XIXe siècle.

Contenu du dépôt :

- `rapport/flaubert.tex`  
  Texte du devoir rédigé en LaTeX (description du corpus, méthode, résultats et interprétation).

- `rapport/analyse_trigrammes.Rmd`  
  Notebook R documentant l’ensemble de la démarche : préparation du corpus,
  essais avec le package Stylo (et difficultés rencontrées),
  puis analyse finale par trigrammes de caractères.

- `rapport/dendrogramme_trigrammes.png`  
  Dendrogramme issu de l’analyse stylométrique fondée sur des trigrammes de caractères.

Méthode (résumé) :

L’analyse repose sur l’extraction de trigrammes de caractères à l’aide du package `quanteda`.
Les distances entre textes sont calculées avec la distance cosine (`proxy`),
puis utilisées pour un clustering hiérarchique (méthode de Ward).

Cette approche permet d’observer des régularités stylistiques liées à la forme de la phrase,
en lien avec la pratique du « gueuloir » chez Gustave Flaubert.

Auteur :

Océane Duhamel 
Université de Genève  
Semestre d’automne 2025–2026
