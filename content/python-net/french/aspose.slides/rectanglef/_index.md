---
title: RectangleF class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: Stocke un ensemble de quatre nombres à virgule flottante qui représentent la position et la taille d'un rectangle.
type: docs
url: /fr/aspose.slides/rectanglef/
net_type: System.Drawing.RectangleF
---
## RectangleF classe

Stocke un ensemble de quatre nombres à virgule flottante qui représentent la position et la taille d’un rectangle. Compatible avec .NET `System.Drawing.RectangleF`.

**Inheritance:**[`RectangleF`](/slides/python-net/fr/aspose.slides/rectanglef) → [`Rectangle`](/slides/python-net/fr/aspose.slides/rectangle)

Le type RectangleF expose les membres suivants :

## Constructeurs

| Constructor | Description |
| :- | :- |
| [`__init__(self, x=0.0, y=0.0, width=0.0, height=0.0)`](/slides/python-net/fr/aspose.slides/rectanglef/__init__/#float-float-float-float) | Crée un rectangle avec la position et la taille spécifiées. |

## Propriétés

| Property | Description |
| :- | :- |
| [`x`](/slides/python-net/fr/aspose.slides/rectanglef/x/) | Obtient la coordonnée x du coin supérieur gauche de ce rectangle.<br/>            Lecture seule **float**. |
| [`y`](/slides/python-net/fr/aspose.slides/rectanglef/y/) | Obtient la coordonnée y du coin supérieur gauche de ce rectangle.<br/>            Lecture seule **float**. |
| [`width`](/slides/python-net/fr/aspose.slides/rectanglef/width/) | Obtient la largeur de ce rectangle.<br/>            Lecture seule **float**. |
| [`height`](/slides/python-net/fr/aspose.slides/rectanglef/height/) | Obtient la hauteur de ce rectangle.<br/>            Lecture seule **float**. |
| [`left`](/slides/python-net/fr/aspose.slides/rectanglef/left/) | Obtient la coordonnée x du bord gauche de ce rectangle. Égal à `x`.<br/>            Lecture seule **float**. |
| [`top`](/slides/python-net/fr/aspose.slides/rectanglef/top/) | Obtient la coordonnée y du bord supérieur de ce rectangle. Égal à `y`.<br/>            Lecture seule **float**. |
| [`right`](/slides/python-net/fr/aspose.slides/rectanglef/right/) | Obtient la coordonnée x qui est la somme de `x` et de `width` de ce rectangle.<br/>            Lecture seule **float**. |
| [`bottom`](/slides/python-net/fr/aspose.slides/rectanglef/bottom/) | Obtient la coordonnée y qui est la somme de `y` et de `height` de ce rectangle.<br/>            Lecture seule **float**. |
| [`is_empty`](/slides/python-net/fr/aspose.slides/rectanglef/is_empty/) | Indique si toutes les propriétés numériques de ce rectangle ont des valeurs zéro.<br/>            Lecture seule **bool**. |

## Méthodes

| Method | Description |
| :- | :- |
| [`contains(self, x, y)`](/slides/python-net/fr/aspose.slides/rectanglef/contains/#float-float) | Détermine si le point spécifié se trouve à l’intérieur de ce rectangle. |
| [`contains(self, point)`](/slides/python-net/fr/aspose.slides/rectanglef/contains/#pointf) | Détermine si le point spécifié se trouve à l’intérieur de ce rectangle. |
| [`contains(self, rect)`](/slides/python-net/fr/aspose.slides/rectanglef/contains/#rectanglef) | Détermine si la région rectangulaire représentée par `rect` est entièrement contenue dans ce rectangle. |


### Remarques

Les rectangles sont comparés par leur position et leur taille avec `==` et peuvent être utilisés comme clés de dictionnaire ou membres d’ensemble.


### Voir aussi
* classe [`Rectangle`](/slides/python-net/fr/aspose.slides/rectangle)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)