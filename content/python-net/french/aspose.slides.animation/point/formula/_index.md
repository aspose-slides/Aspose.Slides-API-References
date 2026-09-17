---
title: formula property
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides.animation/point/formula/
weight: 20
---
## formula propriété
Les formules dans les valeurs, ainsi que les attributs from, to, by, peuvent être composées des éléments suivants :
            Opérateurs arithmétiques standards: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Constantes: ‘pi’ ‘e’
            Opérateurs conditionnels: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Opérateurs de comparaison: '==', '>=', '', '!=', '!'
            Opérateurs trigonométriques: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Logarithme naturel ‘ln()’
            Références de propriétés (propriétés prises en charge par l'hôte)
            
            par exemple: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Lecture/écriture **str**.

### Définition:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```


### Voir aussi
* classe [`Point`](/slides/python-net/fr/aspose.slides.animation/point)
* module [`aspose.slides.animation`](/slides/python-net/fr/aspose.slides.animation)
* bibliothèque [`Aspose.Slides`](/slides/python-net)