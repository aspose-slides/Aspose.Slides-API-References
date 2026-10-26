---
title: cubic_bezier_to method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
Agrega una curva Bezier cúbica al final del trazado


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/es/aspose.slides/pointf) | Primer punto de dirección |
| point2 | [`PointF`](/slides/python-net/es/aspose.slides/pointf) | Segundo punto de dirección |
| point3 | [`PointF`](/slides/python-net/es/aspose.slides/pointf) | Punto final |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
Agrega una curva Bezier cúbica al lugar especificado del trazado


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/es/aspose.slides/pointf) | Primer punto de dirección |
| point2 | [`PointF`](/slides/python-net/es/aspose.slides/pointf) | Segundo punto de dirección |
| point3 | [`PointF`](/slides/python-net/es/aspose.slides/pointf) | Punto final |
| index | **int** | Índice del segmento en PathData |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | El índice del segmento está fuera del rango de PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Agrega una curva Bezier cúbica al final del trazado


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x1 | **float** | Coordenada X del primer punto de dirección |
| y1 | **float** | Coordenada Y del primer punto de dirección |
| x2 | **float** | Coordenada X del segundo punto de dirección |
| y2 | **float** | Coordenada Y del segundo punto de dirección |
| x3 | **float** | Coordenada X del punto final |
| y3 | **float** | Coordenada Y del punto final |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Agrega una curva Bezier cúbica al lugar especificado del trazado


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x1 | **float** | Coordenada X del primer punto de dirección |
| y1 | **float** | Coordenada Y del primer punto de dirección |
| x2 | **float** | Coordenada X del segundo punto de dirección |
| y2 | **float** | Coordenada Y del segundo punto de dirección |
| x3 | **float** | Coordenada X del punto final |
| y3 | **float** | Coordenada Y del punto final |
| index | **int** | Índice del segmento en PathData |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | El índice del segmento está fuera del rango de PathData |



### Ver también
* clase [`GeometryPath`](/slides/python-net/es/aspose.slides/geometrypath)
* clase [`PointF`](/slides/python-net/es/aspose.slides/pointf)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)