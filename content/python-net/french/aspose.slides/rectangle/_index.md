---
title: Rectangle class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: Stocke un ensemble de quatre entiers qui représentent la position et la taille d'un rectangle.
type: docs
url: /fr/aspose.slides/rectangle/
net_type: System.Drawing.Rectangle
---
## Classe Rectangle

Stocke un ensemble de quatre entiers qui représentent la position et la taille d'un rectangle. Compatible avec .NET `System.Drawing.Rectangle`.

Le type Rectangle expose les membres suivants :

## Constructeurs

| Constructeur | Description |
| :- | :- |
| [`__init__(self, x=0, y=0, width=0, height=0)`](/slides/python-net/fr/aspose.slides/rectangle/__init__/#int-int-int-int) | Crée un rectangle avec la position et la taille spécifiées. Les valeurs flottantes sont tronquées en entiers. |

## Propriétés

| Propriété | Description |
| :- | :- |
| [`x`](/slides/python-net/fr/aspose.slides/rectangle/x/) | Obtient la coordonnée x du coin supérieur gauche de ce rectangle.<br/>            Lecture seule **int**. |
| [`y`](/slides/python-net/fr/aspose.slides/rectangle/y/) | Obtient la coordonnée y du coin supérieur gauche de ce rectangle.<br/>            Lecture seule **int**. |
| [`width`](/slides/python-net/fr/aspose.slides/rectangle/width/) | Obtient la largeur de ce rectangle.<br/>            Lecture seule **int**. |
| [`height`](/slides/python-net/fr/aspose.slides/rectangle/height/) | Obtient la hauteur de ce rectangle.<br/>            Lecture seule **int**. |
| [`left`](/slides/python-net/fr/aspose.slides/rectangle/left/) | Obtient la coordonnée x du bord gauche de ce rectangle. Égal à `x`.<br/>            Lecture seule **int**. |
| [`top`](/slides/python-net/fr/aspose.slides/rectangle/top/) | Obtient la coordonnée y du bord supérieur de ce rectangle. Égal à `y`.<br/>            Lecture seule **int**. |
| [`right`](/slides/python-net/fr/aspose.slides/rectangle/right/) | Obtient la coordonnée x qui est la somme de `x` et `width` de ce rectangle.<br/>            Lecture seule **int**. |
| [`bottom`](/slides/python-net/fr/aspose.slides/rectangle/bottom/) | Obtient la coordonnée y qui est la somme de `y` et `height` de ce rectangle.<br/>            Lecture seule **int**. |
| [`is_empty`](/slides/python-net/fr/aspose.slides/rectangle/is_empty/) | Spécifie si toutes les propriétés numériques de ce rectangle ont des valeurs zéro.<br/>            Lecture seule **bool**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/fr/aspose.slides/rectangle/contains/#int-int) | Détermine si le point spécifié est contenu dans ce rectangle. |
| [`contains(self, point)`](/slides/python-net/fr/aspose.slides/rectangle/contains/#point) | Détermine si le point spécifié est contenu dans ce rectangle. |
| [`contains(self, rect)`](/slides/python-net/fr/aspose.slides/rectangle/contains/#rectangle) | Détermine si la région rectangulaire représentée par `rect` est entièrement contenue dans ce rectangle. |

### Remarques

Les rectangles sont comparés par leur position et leur taille avec `==` et peuvent être utilisés comme clés de dictionnaire ou éléments d'ensemble.

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)