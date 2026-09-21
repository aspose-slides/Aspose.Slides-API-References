---
title: formula property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.animation/ipoint/formula/
weight: 10
---
## formule eigenschap
Formules binnen values, from, to, by attributen kunnen bestaan uit de volgende:
            Standaard rekenkundige operatoren: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Constanten: ‘pi’ ‘e’
            Conditionele operatoren: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Vergelijkingsoperatoren: '==', '>=', '', '!=', '!'
            Trigonometische operatoren: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Natuurlijke logaritme ‘ln()’
            Eigendomsverwijzingen (door host ondersteunde eigenschappen)
            
            bijvoorbeeld: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Lezen/schrijven **str**.

### Definitie:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```


### Zie ook
* klasse [`IPoint`](/slides/python-net/nl/aspose.slides.animation/ipoint)
* module [`aspose.slides.animation`](/slides/python-net/nl/aspose.slides.animation)
* bibliotheek [`Aspose.Slides`](/slides/python-net)