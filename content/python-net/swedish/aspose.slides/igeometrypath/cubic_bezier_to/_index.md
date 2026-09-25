---
title: cubic_bezier_to method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
Lägger till en kubisk Bezier-kurva i slutet av vägen


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/sv/aspose.slides/pointf) | Första riktningspunkten |
| point2 | [`PointF`](/slides/python-net/sv/aspose.slides/pointf) | Andra riktningspunkten |
| point3 | [`PointF`](/slides/python-net/sv/aspose.slides/pointf) | Slutpunkt |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
Lägger till en kubisk Bezier-kurva på den angivna platsen i vägen


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/sv/aspose.slides/pointf) | Första riktningspunkten |
| point2 | [`PointF`](/slides/python-net/sv/aspose.slides/pointf) | Andra riktningspunkten |
| point3 | [`PointF`](/slides/python-net/sv/aspose.slides/pointf) | Slutpunkt |
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


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x1 | **float** | X-koordinat för första riktningspunkten |
| y1 | **float** | Y-koordinat för första riktningspunkten |
| x2 | **float** | X-koordinat för andra riktningspunkten |
| y2 | **float** | Y-koordinat för andra riktningspunkten |
| x3 | **float** | X-koordinat för slutpunkten |
| y3 | **float** | Y-koordinat för slutpunkten |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
Lägger till en kubisk Bezier-kurva på den angivna platsen i vägen


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parameter | Typ | Beskrivning |
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



### Se också
* klass [`IGeometryPath`](/slides/python-net/sv/aspose.slides/igeometrypath)
* klass [`PointF`](/slides/python-net/sv/aspose.slides/pointf)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)