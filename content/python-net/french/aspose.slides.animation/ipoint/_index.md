---
title: IPoint class
second_title: Aspose.Slides pour Python via .NET - Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.animation/ipoint/
---
## IPoint classe

Représente un point d'animation.

Le type IPoint expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`time`](/slides/python-net/fr/aspose.slides.animation/ipoint/time/) | Représente une valeur de temps.<br/>            Lecture/écriture **float**. |
| [`value`](/slides/python-net/fr/aspose.slides.animation/ipoint/value/) | Représente une valeur de point.<br/>            Uniquement : bool, ColorFormat, float, int, string.<br/>            Lecture/écriture **any**. |
| [`formula`](/slides/python-net/fr/aspose.slides.animation/ipoint/formula/) | Les formules dans les valeurs, les attributs from, to, by peuvent être composées de ces éléments :<br/>            Opérateurs arithmétiques standards : ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Constantes : ‘pi’ ‘e’<br/>            Opérateurs conditionnels : ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Opérateurs de comparaison : '==', '>=', '', '!=', '!'<br/>            Opérateurs trigonométriques : ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Logarithme naturel ‘ln()’<br/>            Références de propriétés (propriétés prises en charge par l’hôte)<br/>            <br/>            par exemple : "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Lecture/écriture **str**. |

### Voir aussi
* module [`aspose.slides.animation`](/slides/python-net/fr/aspose.slides.animation)
* bibliothèque [`Aspose.Slides`](/slides/python-net)