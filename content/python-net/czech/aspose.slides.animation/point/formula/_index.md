---
title: formula property
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.animation/point/formula/
weight: 20
---
## vzorec vlastnost
Formuly v hodnotách, atributech from, to, by mohou být složeny z těchto:
            Standardní aritmetické operátory: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Konstanty: ‘pi’ ‘e’
            Podmínkové operátory: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Porovnávací operátory: '==', '>=', '', '!=', '!'
            Trigonometrické operátory: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Přirozený logaritmus ‘ln()’
            Odkazy na vlastnosti (vlastnosti podporované hostitelem)
            
            například: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Čtení/Zápis **str**.

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
* třída [`Point`](/slides/python-net/cs/aspose.slides.animation/point)
* modul [`aspose.slides.animation`](/slides/python-net/cs/aspose.slides.animation)
* knihovna [`Aspose.Slides`](/slides/python-net)