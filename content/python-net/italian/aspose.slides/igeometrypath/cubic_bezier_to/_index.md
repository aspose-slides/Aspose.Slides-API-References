---
title: cubic_bezier_to method
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Aggiunge una curva Bezier cubica alla fine del percorso


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Primo punto di direzione |
| point2 | **aspose.slides.PointF** | Secondo punto di direzione |
| point3 | **aspose.slides.PointF** | Punto finale |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Aggiunge una curva Bezier cubica al punto specificato del percorso


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Primo punto di direzione |
| point2 | **aspose.slides.PointF** | Secondo punto di direzione |
| point3 | **aspose.slides.PointF** | Punto finale |
| index | **int** | Indice del segmento in PathData |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | L'indice del segmento è fuori dall'intervallo di PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Aggiunge una curva Bezier cubica alla fine del percorso


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x1 | **float** | Coordinata X del primo punto di direzione |
| y1 | **float** | Coordinata Y del primo punto di direzione |
| x2 | **float** | Coordinata X del secondo punto di direzione |
| y2 | **float** | Coordinata Y del secondo punto di direzione |
| x3 | **float** | Coordinata X del punto finale |
| y3 | **float** | Coordinata Y del punto finale |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Aggiunge una curva Bezier cubica al punto specificato del percorso


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x1 | **float** | Coordinata X del primo punto di direzione |
| y1 | **float** | Coordinata Y del primo punto di direzione |
| x2 | **float** | Coordinata X del secondo punto di direzione |
| y2 | **float** | Coordinata Y del secondo punto di direzione |
| x3 | **float** | Coordinata X del punto finale |
| y3 | **float** | Coordinata Y del punto finale |
| index | **int** | Indice del segmento in PathData |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | L'indice del segmento è fuori dall'intervallo di PathData |



### Vedi anche
* classe [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)