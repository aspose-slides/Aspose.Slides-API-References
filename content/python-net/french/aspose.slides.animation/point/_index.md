---
title: Point class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.animation/point/
---
## Classe Point

Représente un point d'animation.

Le type Point expose les membres suivants :

## Constructeurs

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/fr/aspose.slides.animation/point/__init__/#) | Constructeur par défaut. |
| [`__init__(self, time, value, formula)`](/slides/python-net/fr/aspose.slides.animation/point/__init__/#float-any-str) | Crée un point d'animation avec le temps, la valeur et la formule. |

## Propriétés

| Property | Description |
| :- | :- |
| [`time`](/slides/python-net/fr/aspose.slides.animation/point/time/) | Représente la valeur du temps.<br/>            Lecture/écriture **float**. |
| [`value`](/slides/python-net/fr/aspose.slides.animation/point/value/) | Représente la valeur du point.<br/>            Uniquement : bool, ColorFormat, float, int, string.<br/>            Lecture/écriture **any**. |
| [`formula`](/slides/python-net/fr/aspose.slides.animation/point/formula/) | Les formules dans les valeurs, attributs from, to, by peuvent être composées de ces éléments :<br/>            Opérateurs arithmétiques standards : ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Constantes : ‘pi’ ‘e’<br/>            Opérateurs conditionnels : ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Opérateurs de comparaison : '==', '>=', '', '!=', '!'<br/>            Opérateurs trigonométriques : ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Logarithme naturel ‘ln()’<br/>            Références de propriétés (propriétés prises en charge par l'hôte)<br/>            <br/>            par exemple : "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Lecture/écriture **str**. |

### Voir aussi
* module [`aspose.slides.animation`](/slides/python-net/fr/aspose.slides.animation)
* bibliothèque [`Aspose.Slides`](/slides/python-net)