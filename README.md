# Exercice de collaboration avec Git et GitHub

## Introduction

Cet exercice vous permettra de vous familiariser avec les aspects collaboratifs de Git et GitHub. Vous apprendrez à travailler sur un projet commun, à faire des modifications, et à les intégrer au dépôt principal via des pull requests.

## Structure du projet

```
collaboration-projet/
  ├── src/
  │   └── main.c
  └── README.md
```

## Le programme initial

Le programme de base est un simple affichage en C :

```c
#include <stdio.h>

int main() {
  printf("Piscine Prep 2025\n");
  return 0;
}
```

## Objectifs

1. Créer un fork du dépôt principal sur votre compte GitHub
2. Cloner votre fork sur votre machine locale
3. Créer une branche pour vos modifications
4. Modifier le programme pour ajouter votre nom
5. Pousser vos modifications vers votre fork
6. Créer une pull request pour proposer l'intégration de vos modifications au dépôt principal

## Résultat attendu

À la fin de cet exercice, le programme devra afficher "Piscine Prep 2025" suivi d'une liste des noms de tous les étudiants ayant participé. Par exemple :

```
Piscine Prep 2025
- Ornil
- Randy
- Selim
- Alisa
- Mateo
- Ozairullah
- Erkan
- Umit
- Tenzin
```

## Consignes détaillées

### Partie 1 : Préparation

1. Créez un fork du dépôt principal sur votre compte GitHub (cherchez le bouton "Fork" sur la page du dépôt)
2. Clonez votre fork sur votre machine locale
3. Configurez un "remote" pointant vers le dépôt principal (appelé conventionnellement "upstream")

### Partie 2 : Développement

1. Créez une nouvelle branche nommée selon le format `ajout-nom-prenom`
2. Modifiez le fichier `src/main.c` pour ajouter une ligne qui affiche votre nom
3. Compilez et testez votre code pour vous assurer qu'il fonctionne correctement
4. Commitez vos modifications avec un message descriptif

### Partie 3 : Partage

1. Synchronisez votre dépôt local avec le dépôt principal pour intégrer les éventuelles modifications récentes
2. Résolvez les conflits éventuels
3. Poussez votre branche vers votre fork
4. Créez une pull request depuis votre branche vers la branche principale du dépôt d'origine

## Règles

- Chaque étudiant doit créer sa propre branche et sa propre pull request
- Ne modifiez que la partie du code qui concerne l'affichage des noms
- Respectez le format d'affichage demandé
- Ne supprimez pas les noms déjà ajoutés par d'autres étudiants
- Résolvez les conflits de manière appropriée si nécessaire
