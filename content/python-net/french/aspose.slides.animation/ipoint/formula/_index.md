---
title: formula property
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.animation/ipoint/formula/
weight: 10
---
## formula propriété
Les formules dans les attributs values, from, to, by peuvent être composées de ces éléments :
            Opérateurs arithmétiques standards : ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Constantes : ‘pi’ ‘e’
            Opérateurs conditionnels : ‘abs’, ‘min’, ‘max’, ‘?’ (si)
            Opérateurs de comparaison : '==', '>=', '', '!=', '!'
            Opérateurs trigonométriques : ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Logarithme naturel ‘ln()’
            Références de propriété (propriétés prises en charge par l’hôte)
            
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
* classe [`IPoint`](/slides/python-net/fr/aspose.slides.animation/ipoint)
* module [`aspose.slides.animation`](/slides/python-net/fr/aspose.slides.animation)
* bibliothèque [`Aspose.Slides`](/slides/python-net)