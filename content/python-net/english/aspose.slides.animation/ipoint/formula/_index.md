---
title: formula property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.animation/ipoint/formula/
weight: 10
---


## formula property
Formulas within values, from, to, by attributes can be made up of these:
            Standard arithmetic operators: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Constants: ‘pi’ ‘e’
            Conditional operators: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Comparison operators: '==', '>=', '', '!=', '!'
            Trigonometric operators: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Natural logarithm ‘ln()’
            Property references (host supported properties)
            
            for example: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Read/write .NET type System.String.

### Definition:
```python
@property
def formula(self):
    ...
@formula.setter
def formula(self, value):
    ...
```
