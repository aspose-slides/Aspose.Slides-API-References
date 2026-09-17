---
title: quadratic_bezier_to method
second_title: Referencia de la API Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
Añade una curva Bézier cuadrática al final de la ruta


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Punto de dirección |
| point2 | **aspose.slides.PointF** | Punto final |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
Añade una curva Bézier cuadrática al lugar especificado de la ruta


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Punto de dirección |
| point2 | **aspose.slides.PointF** | Punto final |
| index | **int** | Índice del segmento en PathData |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | El índice del segmento está fuera del rango de PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Añade una curva Bézier cuadrática al final de la ruta


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
Añade una curva Bézier cuadrática al lugar especificado de la ruta


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
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)