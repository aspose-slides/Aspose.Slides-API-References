---
title: formula property
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.animation/ipoint/formula/
weight: 10
---
## proprietà formula
Formulas within values, from, to, by attributes can be made up of these:
            Operatori aritmetici standard: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Costanti: ‘pi’ ‘e’
            Operatori condizionali: ‘abs’, ‘min’, ‘max’, ‘?’ (se)
            Operatori di confronto: '==', '>=', '', '!=', '!'
            Operatori trigonometrici: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Logaritmo naturale ‘ln()’
            Riferimenti alle proprietà (proprietà supportate dall'host)
            
            per esempio: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Lettura/scrittura **str**.

### Definizione:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```

### Vedi anche
* classe [`IPoint`](/slides/python-net/it/aspose.slides.animation/ipoint)
* modulo [`aspose.slides.animation`](/slides/python-net/it/aspose.slides.animation)
* libreria [`Aspose.Slides`](/slides/python-net)