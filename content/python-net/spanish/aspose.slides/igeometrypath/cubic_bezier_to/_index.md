---
title: cubic_bezier_to method
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Agrega una curva cúbica de Bézier al final del trazado


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Primer punto de dirección |
| point2 | **aspose.slides.PointF** | Segundo punto de dirección |
| point3 | **aspose.slides.PointF** | Punto final |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Agrega una curva cúbica de Bézier al lugar especificado del trazado


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Primer punto de dirección |
| point2 | **aspose.slides.PointF** | Segundo punto de dirección |
| point3 | **aspose.slides.PointF** | Punto final |
| index | **int** | Índice del segmento en PathData |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment index is out of PathData range |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Agrega una curva cúbica de Bézier al final del trazado


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
Agrega una curva cúbica de Bézier al lugar especificado del trazado


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
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segment index is out of PathData range |



### Ver también
* clase [`IGeometryPath`](/slides/python-net/es/aspose.slides/igeometrypath)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)