---
title: quadratic_bezier_to method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
Agrega una curva cuadrática de Bézier al final de la ruta

```python
def quadratic_bezier_to(self, point1, point2):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Punto de dirección |
| point2 | **aspose.slides.PointF** | Punto final |

## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
Agrega una curva cuadrática de Bézier al lugar especificado de la ruta

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
Agrega una curva cuadrática de Bézier al final de la ruta

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
Agrega una curva cuadrática de Bézier al lugar especificado de la ruta

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
* clase [`GeometryPath`](/slides/python-net/es/aspose.slides/geometrypath)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)