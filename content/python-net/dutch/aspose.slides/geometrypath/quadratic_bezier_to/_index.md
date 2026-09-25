---
title: quadratic_bezier_to method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
Voegt een kwadratische Bezier-curve toe aan het einde van het pad


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/nl/aspose.slides/pointf) | Richtingspunt |
| point2 | [`PointF`](/slides/python-net/nl/aspose.slides/pointf) | Eindpunt |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
Voegt een kwadratische Bezier-curve toe op de opgegeven plaats van het pad


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/nl/aspose.slides/pointf) | Richtingspunt |
| point2 | [`PointF`](/slides/python-net/nl/aspose.slides/pointf) | Eindpunt |
| index | **int** | Index van segment in PathData |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex is buiten het bereik van PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Voegt een kwadratische Bezier-curve toe aan het einde van het pad


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x1 | **float** | X-coördinaat van richtingspunt |
| y1 | **float** | Y-coördinaat van richtingspunt |
| x2 | **float** | X-coördinaat van eindpunt |
| y2 | **float** | Y-coördinaat van eindpunt |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Voegt een kwadratische Bezier-curve toe op de opgegeven plaats van het pad


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x1 | **float** | X-coördinaat van richtingspunt |
| y1 | **float** | Y-coördinaat van richtingspunt |
| x2 | **float** | X-coördinaat van eindpunt |
| y2 | **float** | Y-coördinaat van eindpunt |
| index | **int** | Index van segment in PathData |

### Uitzonderingen

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex is buiten het bereik van PathData |



### Zie ook
* klasse [`GeometryPath`](/slides/python-net/nl/aspose.slides/geometrypath)
* klasse [`PointF`](/slides/python-net/nl/aspose.slides/pointf)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)