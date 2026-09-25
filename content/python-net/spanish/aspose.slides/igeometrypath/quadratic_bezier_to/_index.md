---
title: quadratic_bezier_to method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
Agrega una curva Bézier cuadrática al final de la ruta


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/es/aspose.slides/pointf) | Punto de dirección |
| point2 | [`PointF`](/slides/python-net/es/aspose.slides/pointf) | Punto final |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
Agrega una curva Bézier cuadrática en el lugar especificado de la ruta


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/es/aspose.slides/pointf) | Punto de dirección |
| point2 | [`PointF`](/slides/python-net/es/aspose.slides/pointf) | Punto final |
| index | **int** | Índice del segmento en PathData |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | El índice del segmento está fuera del rango de PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Agrega una curva Bézier cuadrática al final de la ruta


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x1 | **float** | Coordenada X del punto de dirección |
| y1 | **float** | Coordenada Y del punto de dirección |
| x2 | **float** | Coordenada X del punto final |
| y2 | **float** | Coordenada Y del punto final |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Agrega una curva Bézier cuadrática en el lugar especificado de la ruta


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x1 | **float** | Coordenada X del punto de dirección |
| y1 | **float** | Coordenada Y del punto de dirección |
| x2 | **float** | Coordenada X del punto final |
| y2 | **float** | Coordenada Y del punto final |
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