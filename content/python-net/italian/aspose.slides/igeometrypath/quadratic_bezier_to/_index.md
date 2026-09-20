---
title: quadratic_bezier_to method
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
Aggiunge una curva Bézier quadratica alla fine del percorso


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Punto di direzione |
| point2 | **aspose.slides.PointF** | Punto finale |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
Aggiunge una curva Bézier quadratica al punto specificato del percorso


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Punto di direzione |
| point2 | **aspose.slides.PointF** | Punto finale |
| index | **int** | Indice del segmento in PathData |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | L'indice del segmento è fuori dall'intervallo di PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Aggiunge una curva Bézier quadratica alla fine del percorso


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x1 | **float** | Coordinata X del punto di direzione |
| y1 | **float** | Coordinata Y del punto di direzione |
| x2 | **float** | Coordinata X del punto finale |
| y2 | **float** | Coordinata Y del punto finale |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Aggiunge una curva Bézier quadratica al punto specificato del percorso


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x1 | **float** | Coordinata X del punto di direzione |
| y1 | **float** | Coordinata Y del punto di direzione |
| x2 | **float** | Coordinata X del punto finale |
| y2 | **float** | Coordinata Y del punto finale |
| index | **int** | Indice del segmento in PathData |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | L'indice del segmento è fuori dall'intervallo di PathData |



### Vedi anche
* classe [`IGeometryPath`](/slides/python-net/it/aspose.slides/igeometrypath)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)