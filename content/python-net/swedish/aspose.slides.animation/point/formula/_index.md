---
title: formula property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.animation/point/formula/
weight: 20
---
## formulegenskap
Formler inom värden, från, till, av attribut kan bestå av följande:
            Standardaritmetiska operatorer: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Konstanter: ‘pi’ ‘e’
            Villkorsoperatorer: ‘abs’, ‘min’, ‘max’, ‘?’ (om)
            Jämförelseoperatorer: '==', '>=', '', '!=', '!'
            Trigonometriska operatorer: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Naturlig logaritm ‘ln()’
            Egendomsreferenser (värdstödda egenskaper)
            
            till exempel: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Läs/skriv **str**.

### Definition:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```

### Se även
* klass [`Point`](/slides/python-net/sv/aspose.slides.animation/point)
* modul [`aspose.slides.animation`](/slides/python-net/sv/aspose.slides.animation)
* bibliotek [`Aspose.Slides`](/slides/python-net)