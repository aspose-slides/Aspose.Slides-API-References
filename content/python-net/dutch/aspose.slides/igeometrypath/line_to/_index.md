---
title: line_to method
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposepydrawingpointf}
Voegt een lijn toe aan het einde van het pad


```python
def line_to(self, point):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Eindpunt van de lijn |


## line_to(self, x, y) {#float-float}
Voegt een lijn toe aan het einde van het pad


```python
def line_to(self, x, y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | **float** | X-coördinaat van het eindpunt van de lijn |
| y | **float** | Y-coördinaat van het eindpunt van de lijn |


## line_to(self, point, index) {#asposepydrawingpointf-int}
Voegt een lijn toe op de opgegeven plaats van het pad


```python
def line_to(self, point, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Eindpunt |
| index | **int** | Index van segment in PathData |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex is buiten het bereik van PathData |


## line_to(self, x, y, index) {#float-float-int}
Voegt een lijn toe op de opgegeven plaats van het pad


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | **float** | X-coördinaat van het punt |
| y | **float** | Y-coördinaat van het punt |
| index | **int** | Index van segment in PathData |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Segmentindex is buiten het bereik van PathData |



### Zie ook
* klasse [`IGeometryPath`](/slides/python-net/nl/aspose.slides/igeometrypath)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)