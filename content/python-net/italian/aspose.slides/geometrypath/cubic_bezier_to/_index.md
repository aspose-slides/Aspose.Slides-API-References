---
title: cubic_bezier_to method
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
Aggiunge una curva Bézier cubica alla fine del percorso


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/it/aspose.slides/pointf) | Primo punto di direzione |
| point2 | [`PointF`](/slides/python-net/it/aspose.slides/pointf) | Secondo punto di direzione |
| point3 | [`PointF`](/slides/python-net/it/aspose.slides/pointf) | Punto finale |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
Aggiunge una curva Bézier cubica al punto specificato del percorso


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/it/aspose.slides/pointf) | Primo punto di direzione |
| point2 | [`PointF`](/slides/python-net/it/aspose.slides/pointf) | Secondo punto di direzione |
| point3 | [`PointF`](/slides/python-net/it/aspose.slides/pointf) | Punto finale |
| index | **int** | Indice del segmento in PathData |

### Eccezioni

| Eccezione | Descrizione |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | L'indice del segmento è fuori dall'intervallo di PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Aggiunge una curva Bézier cubica alla fine del percorso


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
Aggiunge una curva Bézier cubica al punto specificato del percorso


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
* classe [`GeometryPath`](/slides/python-net/it/aspose.slides/geometrypath)
* classe [`PointF`](/slides/python-net/it/aspose.slides/pointf)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)