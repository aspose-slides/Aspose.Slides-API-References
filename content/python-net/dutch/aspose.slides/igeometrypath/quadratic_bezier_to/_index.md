---
title: quadratic_bezier_to method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
Voegt een kwadratische Bezierkromme toe aan het einde van het pad


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Richtpunt |
| point2 | **aspose.slides.PointF** | Eindpunt |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
Voegt een kwadratische Bezierkromme toe op de opgegeven plaats van het pad


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Richtpunt |
| point2 | **aspose.slides.PointF** | Eindpunt |
| index | **int** | Index van segment in PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex ligt buiten het bereik van PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Voegt een kwadratische Bezierkromme toe aan het einde van het pad


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | X-coördinaat van richtpunt |
| y1 | **float** | Y-coördinaat van richtpunt |
| x2 | **float** | X-coördinaat van eindpunt |
| y2 | **float** | Y-coördinaat van eindpunt |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Voegt een kwadratische Bezierkromme toe op de opgegeven plaats van het pad


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | X-coördinaat van richtpunt |
| y1 | **float** | Y-coördinaat van richtpunt |
| x2 | **float** | X-coördinaat van eindpunt |
| y2 | **float** | Y-coördinaat van eindpunt |
| index | **int** | Index van segment in PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex ligt buiten het bereik van PathData |



### See Also
* class [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)