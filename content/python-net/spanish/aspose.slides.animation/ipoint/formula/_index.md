---
title: formula property
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.animation/ipoint/formula/
weight: 10
---
## propiedad de fórmula
Las fórmulas dentro de los valores, atributos from, to, by pueden estar formadas por los siguientes:
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
* clase [`IPoint`](/slides/python-net/es/aspose.slides.animation/ipoint)
* módulo [`aspose.slides.animation`](/slides/python-net/es/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)