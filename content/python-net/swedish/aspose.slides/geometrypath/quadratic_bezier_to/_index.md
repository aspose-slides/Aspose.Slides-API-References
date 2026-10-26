---
title: quadratic_bezier_to method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
Lägger till en kvadratisk Bezier-kurva i slutet av sökvägen

```python
def quadratic_bezier_to(self, point1, point2):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/sv/aspose.slides/pointf) | Riktningpunkt |
| point2 | [`PointF`](/slides/python-net/sv/aspose.slides/pointf) | Slutpunkt |

## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
Lägger till en kvadratisk Bezier-kurva på den angivna platsen i sökvägen

```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/sv/aspose.slides/pointf) | Riktningpunkt |
| point2 | [`PointF`](/slides/python-net/sv/aspose.slides/pointf) | Slutpunkt |
| index | **int** | Index för segment i PathData |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex är utanför PathData-intervallet |

## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
Lägger till en kvadratisk Bezier-kurva i slutet av sökvägen

```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x1 | **float** | X-koordinat för riktningpunkt |
| y1 | **float** | Y-koordinat för riktningpunkt |
| x2 | **float** | X-koordinat för slutpunkt |
| y2 | **float** | Y-koordinat för slutpunkt |

## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
Lägger till en kvadratisk Bezier-kurva på den angivna platsen i sökvägen

```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x1 | **float** | X-koordinat för riktningpunkt |
| y1 | **float** | Y-koordinat för riktningpunkt |
| x2 | **float** | X-koordinat för slutpunkt |
| y2 | **float** | Y-koordinat för slutpunkt |
| index | **int** | Index för segment i PathData |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex är utanför PathData-intervallet |

### Se även
* klass [`GeometryPath`](/slides/python-net/sv/aspose.slides/geometrypath)
* klass [`PointF`](/slides/python-net/sv/aspose.slides/pointf)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)