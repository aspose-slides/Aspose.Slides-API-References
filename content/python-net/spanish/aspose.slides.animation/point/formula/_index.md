---
title: formula property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.animation/point/formula/
weight: 20
---
## propiedad de fórmula
Fórmulas dentro de values, from, to, by atributos pueden estar compuestas por los siguientes:
            Operadores aritméticos estándar: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Constantes: ‘pi’ ‘e’
            Operadores condicionales: ‘abs’, ‘min’, ‘max’, ‘?’ (si)
            Operadores de comparación: '==', '>=', '', '!=', '!'
            Operadores trigonométricos: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Logaritmo natural ‘ln()’
            Referencias a propiedades (propiedades soportadas por el host)
            
            por ejemplo: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
            Lectura/escritura **str**.

### Definición:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```

### Ver también
* clase [`Point`](/slides/python-net/es/aspose.slides.animation/point)
* módulo [`aspose.slides.animation`](/slides/python-net/es/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)