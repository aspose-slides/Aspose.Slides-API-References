---
title: formula property
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides.animation/ipoint/formula/
weight: 10
---
## formula vlastnost
Formuly v hodnotách, atributech from, to, by mohou být složeny z následujícího:
            Standardní aritmetické operátory: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Konstanty: ‘pi’ ‘e’
            Podmíněné operátory: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Porovnávací operátory: '==', '>=', '', '!=', '!'
            Trigonometrické operátory: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Přirozený logaritmus ‘ln()’
            Odkazy na vlastnosti (host podporované vlastnosti)
            
            například: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Číst/zapisovat **str**.

### Definice:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```

### Viz také
* třída [`IPoint`](/slides/python-net/cs/aspose.slides.animation/ipoint)
* modul [`aspose.slides.animation`](/slides/python-net/cs/aspose.slides.animation)
* knihovna [`Aspose.Slides`](/slides/python-net)