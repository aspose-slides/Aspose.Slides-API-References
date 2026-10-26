---
title: contains method
second_title: Referencia de la API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Determina si el punto especificado está contenido dentro de este rectángulo.

### Returns

`True` si el punto está contenido dentro de este rectángulo; de lo contrario, `False`.



```python
def contains(self, point):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/es/aspose.slides/pointf) | El punto a probar. Se acepta cualquier objeto con atributos `x` y `y`. |

### Exceptions

| Excepción | Descripción |
| :- | :- |
| **TypeError** | Número incorrecto de argumentos. |


## contains(self, rect) {#rectanglef}
Determina si la región rectangular representada por `rect` está completamente contenida dentro de este rectángulo.

### Returns

`True` si la región rectangular representada por `rect` está completamente contenida dentro de este rectángulo; de lo contrario, `False`.



```python
def contains(self, rect):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/es/aspose.slides/rectanglef) | El rectángulo a probar. Se acepta cualquier objeto con atributos `x`, `y`, `width` y `height`. |

### Exceptions

| Excepción | Descripción |
| :- | :- |
| **TypeError** | Número incorrecto de argumentos. |


## contains(self, x, y) {#float-float}
Determina si el punto especificado está contenido dentro de este rectángulo.

### Returns

`True` si el punto definido por `x` y `y` está contenido dentro de este rectángulo; de lo contrario, `False`.



```python
def contains(self, x, y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | **float** | La coordenada x del punto a probar. |
| y | **float** | La coordenada y del punto a probar. |

### Exceptions

| Excepción | Descripción |
| :- | :- |
| **TypeError** | Número incorrecto de argumentos. |



### See Also
* clase [`PointF`](/slides/python-net/es/aspose.slides/pointf)
* clase [`RectangleF`](/slides/python-net/es/aspose.slides/rectanglef)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)