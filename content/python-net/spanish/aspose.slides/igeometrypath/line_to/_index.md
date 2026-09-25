---
title: line_to method
second_title: Aspose.Slides para Python mediante la referencia de la API .NET
description: 
type: docs
url: /es/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposeslidespointf}
Agrega una línea al final de la ruta


```python
def line_to(self, point):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/es/aspose.slides/pointf) | Punto final de la línea |


## line_to(self, x, y) {#float-float}
Agrega una línea al final de la ruta


```python
def line_to(self, x, y):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | **float** | Coordenada X del punto final de la línea |
| y | **float** | Coordenada Y del punto final de la línea |


## line_to(self, point, index) {#asposeslidespointf-int}
Agrega una línea al lugar especificado de la ruta


```python
def line_to(self, point, index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/es/aspose.slides/pointf) | Punto final |
| index | **int** | Índice del segmento en PathData |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | El índice del segmento está fuera del rango de PathData |


## line_to(self, x, y, index) {#float-float-int}
Agrega una línea al lugar especificado de la ruta


```python
def line_to(self, x, y, index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | **float** | Coordenada X del punto |
| y | **float** | Coordenada Y del punto |
| index | **int** | Índice del segmento en PathData |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | El índice del segmento está fuera del rango de PathData |



### Ver también
* clase [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath)
* clase [`PointF`](/slides/python-net/es/aspose.slides/pointf)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)