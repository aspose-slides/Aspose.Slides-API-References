---
title: formula property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.animation/point/formula/
weight: 20
---
## Formeleigenschaft
Formeln innerhalb von Werten, from, to, by Attributen können aus folgenden Bestandteilen bestehen:
            Standardarithmetische Operatoren: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Konstanten: ‘pi’ ‘e’
            Bedingte Operatoren: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Vergleichsoperatoren: '==', '>=', '', '!=', '!'
            Trigonometrische Operatoren: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Natürlicher Logarithmus ‘ln()’
            Eigenschaftsreferenzen (vom Host unterstützte Eigenschaften)
            
            zum Beispiel: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Lesen/Schreiben **str**.

### Definition:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```


### Siehe auch
* Klasse [`Point`](/slides/python-net/de/aspose.slides.animation/point)
* Modul [`aspose.slides.animation`](/slides/python-net/de/aspose.slides.animation)
* Bibliothek [`Aspose.Slides`](/slides/python-net)