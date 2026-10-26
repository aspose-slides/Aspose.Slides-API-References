---
title: formula property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.animation/point/formula/
weight: 20
---
## formula eigenschap
Formules binnen waarden, van, tot, door attributen kunnen bestaan uit de volgende:
            Standaard rekenoperatoren: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Constanten: ‘pi’ ‘e’
            Conditionele operatoren: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Vergelijkingsoperatoren: '==', '>=', '', '!=', '!'
            Trigonometrische operatoren: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Natuurlijke logaritme ‘ln()’
            Eigenschapverwijzingen (door host ondersteunde eigenschappen)
            
            for example: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
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
* klasse [`Point`](/slides/python-net/nl/aspose.slides.animation/point)
* module [`aspose.slides.animation`](/slides/python-net/nl/aspose.slides.animation)
* bibliotheek [`Aspose.Slides`](/slides/python-net)