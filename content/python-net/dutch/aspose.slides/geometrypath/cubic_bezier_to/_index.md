---
title: cubic_bezier_to method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Voegt een kubieke Bezier-curve toe aan het einde van het pad


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Eerste richtingspunt |
| point2 | **aspose.slides.PointF** | Tweede richtingspunt |
| point3 | **aspose.slides.PointF** | Eindpunt |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Voegt een kubieke Bezier-curve toe op de opgegeven plaats van het pad


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Eerste richtingspunt |
| point2 | **aspose.slides.PointF** | Tweede richtingspunt |
| point3 | **aspose.slides.PointF** | Eindpunt |
| index | **int** | Index van segment in PathData |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex is buiten het bereik van PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Voegt een kubieke Bezier-curve toe aan het einde van het pad


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x1 | **float** | X-coördinaat van het eerste richtingspunt |
| y1 | **float** | Y-coördinaat van het eerste richtingspunt |
| x2 | **float** | X-coördinaat van het tweede richtingspunt |
| y2 | **float** | Y-coördinaat van het tweede richtingspunt |
| x3 | **float** | X-coördinaat van het eindpunt |
| y3 | **float** | Y-coördinaat van het eindpunt |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Voegt een kubieke Bezier-curve toe op de opgegeven plaats van het pad


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x1 | **float** | X-coördinaat van het eerste richtingspunt |
| y1 | **float** | Y-coördinaat van het eerste richtingspunt |
| x2 | **float** | X-coördinaat van het tweede richtingspunt |
| y2 | **float** | Y-coördinaat van het tweede richtingspunt |
| x3 | **float** | X-coördinaat van het eindpunt |
| y3 | **float** | Y-coördinaat van het eindpunt |
| index | **int** | Index van segment in PathData |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex is buiten het bereik van PathData |



### Zie ook
* klasse [`GeometryPath`](/slides/python-net/nl/aspose.slides/geometrypath)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)