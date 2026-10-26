---
title: Point class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.animation/point/
---
## Clase Point

Representa un punto de animación.

El tipo Point expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.animation/point/__init__/#) | Constructor por defecto. |
| [`__init__(self, time, value, formula)`](/slides/python-net/es/aspose.slides.animation/point/__init__/#float-any-str) | Crea un punto de animación con tiempo, valor y fórmula. |

## Propiedades

| Property | Descripción |
| :- | :- |
| [`time`](/slides/python-net/es/aspose.slides.animation/point/time/) | Representa el valor de tiempo.<br/>            Lectura/escritura **float**. |
| [`value`](/slides/python-net/es/aspose.slides.animation/point/value/) | Representa el valor del punto.<br/>            Solo: bool, ColorFormat, float, int, string.<br/>            Lectura/escritura **any**. |
| [`formula`](/slides/python-net/es/aspose.slides.animation/point/formula/) | Las fórmulas dentro de los valores, atributos from, to, by pueden estar compuestas por:<br/>            Operadores aritméticos estándar: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Constantes: ‘pi’ ‘e’<br/>            Operadores condicionales: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Operadores de comparación: '==', '>=', '', '!=', '!'<br/>            Operadores trigonométricos: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Logaritmo natural ‘ln()’<br/>            Referencias a propiedades (propiedades admitidas por el host)<br/>            <br/>            por ejemplo: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Lectura/escritura **str**. |

### Ver también
* módulo [`aspose.slides.animation`](/slides/python-net/es/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)