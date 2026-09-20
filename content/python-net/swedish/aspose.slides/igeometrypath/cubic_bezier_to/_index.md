---
title: cubic_bezier_to method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
Lägger till en kubisk Bezier-kurva i slutet av vägen


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parameter | Type | Beskrivning |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Första riktningspunkten |
| point2 | **aspose.slides.PointF** | Andra riktningspunkten |
| point3 | **aspose.slides.PointF** | Slutpunkt |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
Lägger till en kubisk Bezier-kurva på den specificerade platsen i vägen


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parameter | Type | Beskrivning |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | Första riktningspunkten |
| point2 | **aspose.slides.PointF** | Andra riktningspunkten |
| point3 | **aspose.slides.PointF** | Slutpunkt |
| index | **int** | Index för segment i PathData |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex är utanför PathData-intervallet |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
Lägger till en kubisk Bezier-kurva i slutet av vägen


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parameter | Type | Beskrivning |
| :- | :- | :- |
| x1 | **float** | X-koordinat för första riktningspunkten |
| y1 | **float** | Y-koordinat för första riktningspunkten |
| x2 | **float** | X-koordinat för andra riktningspunkten |
| y2 | **float** | Y-koordinat för andra riktningspunkten |
| x3 | **float** | X-koordinat för slutpunkten |
| y3 | **float** | Y-koordinat för slutpunkten |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Lägger till en kubisk Bezier-kurva på den specificerade platsen i vägen


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parameter | Type | Beskrivning |
| :- | :- | :- |
| x1 | **float** | X-koordinat för första riktningspunkten |
| y1 | **float** | Y-koordinat för första riktningspunkten |
| x2 | **float** | X-koordinat för andra riktningspunkten |
| y2 | **float** | Y-koordinat för andra riktningspunkten |
| x3 | **float** | X-koordinat för slutpunkten |
| y3 | **float** | Y-koordinat för slutpunkten |
| index | **int** | Index för segment i PathData |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex är utanför PathData-intervallet |



### Se även
* klass [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)