---
title: cubic_bezier_to method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
Voegt een kubieke Bézier-curve toe aan het einde van het pad


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/nl/aspose.slides/pointf) | Eerste richtingspunt |
| point2 | [`PointF`](/slides/python-net/nl/aspose.slides/pointf) | Tweede richtingspunt |
| point3 | [`PointF`](/slides/python-net/nl/aspose.slides/pointf) | Eindpunt |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
Voegt een kubieke Bézier-curve toe op de opgegeven plaats van het pad


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/nl/aspose.slides/pointf) | Eerste richtingspunt |
| point2 | [`PointF`](/slides/python-net/nl/aspose.slides/pointf) | Tweede richtingspunt |
| point3 | [`PointF`](/slides/python-net/nl/aspose.slides/pointf) | Eindpunt |
| index | **int** | Index van segment in PathData |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex is buiten het bereik van PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Voegt een kubieke Bézier-curve toe aan het einde van het pad


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x1 | **float** | X-coördinaat van eerste richtingspunt |
| y1 | **float** | Y-coördinaat van eerste richtingspunt |
| x2 | **float** | X-coördinaat van tweede richtingspunt |
| y2 | **float** | Y-coördinaat van tweede richtingspunt |
| x3 | **float** | X-coördinaat van eindpunt |
| y3 | **float** | Y-coördinaat van eindpunt |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Voegt een kubieke Bézier-curve toe op de opgegeven plaats van het pad


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x1 | **float** | X-coördinaat van eerste richtingspunt |
| y1 | **float** | Y-coördinaat van eerste richtingspunt |
| x2 | **float** | X-coördinaat van tweede richtingspunt |
| y2 | **float** | Y-coördinaat van tweede richtingspunt |
| x3 | **float** | X-coördinaat van eindpunt |
| y3 | **float** | Y-coördinaat van eindpunt |
| index | **int** | Index van segment in PathData |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex is buiten het bereik van PathData |



### Zie ook
* klasse [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)
* klasse [`PointF`](/slides/python-net/nl/aspose.slides/pointf)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)