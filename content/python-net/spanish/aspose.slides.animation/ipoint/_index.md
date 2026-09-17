---
title: IPoint class
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.animation/ipoint/
---
## IPoint clase

Representa un punto de animación.

El tipo IPoint expone los siguientes miembros:

## Propiedades

| Propiedad | Descripción |
| :- | :- |
| [`time`](/slides/python-net/es/aspose.slides.animation/ipoint/time/) | Representa el valor de tiempo.<br/>            Lectura/escritura **float**. |
| [`value`](/slides/python-net/es/aspose.slides.animation/ipoint/value/) | Representa el valor del punto.<br/>            Solo: bool, ColorFormat, float, int, string.<br/>            Lectura/escritura **any**. |
| [`formula`](/slides/python-net/es/aspose.slides.animation/ipoint/formula/) | Las fórmulas dentro de los valores, atributos from, to, by pueden estar compuestas por lo siguiente:<br/>            Operadores aritméticos estándar: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)<br/>            Constantes: ‘pi’ ‘e’<br/>            Operadores condicionales: ‘abs’, ‘min’, ‘max’, ‘?’ (if)<br/>            Operadores de comparación: '==', '>=', '', '!=', '!'<br/>            Operadores trigonométricos: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’<br/>            Logaritmo natural ‘ln()’<br/>            Referencias a propiedades (propiedades compatibles con el host)<br/>            <br/>            por ejemplo: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"<br/>            Lectura/escritura **str**. |


### Ver también
* módulo [`aspose.slides.animation`](/slides/python-net/es/aspose.slides.animation)
* biblioteca [`Aspose.Slides`](/slides/python-net)