---
title: contains method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Determina si el punto especificado está contenido dentro de este rectángulo.

### Devuelve

`True` si el punto está contenido dentro de este rectángulo; de lo contrario, `False`.



```python
def contains(self, point):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/es/aspose.slides/point) | El punto a probar. Cualquier objeto con atributos `x` y `y` es aceptado. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **TypeError** | Número incorrecto de argumentos. |


## contains(self, rect) {#rectangle}
Determina si la región rectangular representada por `rect` está contenida completamente dentro de este rectángulo.

### Devuelve

`True` si la región rectangular representada por `rect` está contenida completamente dentro de este rectángulo; de lo contrario, `False`.



```python
def contains(self, rect):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/es/aspose.slides/rectangle) | El rectángulo a probar. Cualquier objeto con atributos `x`, `y`, `width` y `height` es aceptado. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **TypeError** | Número incorrecto de argumentos. |


## contains(self, x, y) {#int-int}
Determina si el punto especificado está contenido dentro de este rectángulo.

### Devuelve

`True` si el punto definido por `x` y `y` está contenido dentro de este rectángulo; de lo contrario, `False`.



```python
def contains(self, x, y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | **int** | La coordenada x del punto a probar. |
| y | **int** | La coordenada y del punto a probar. |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **TypeError** | Número incorrecto de argumentos. |



### Ver también
* clase [`Point`](/slides/python-net/es/aspose.slides/point)
* clase [`Rectangle`](/slides/python-net/es/aspose.slides/rectangle)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)