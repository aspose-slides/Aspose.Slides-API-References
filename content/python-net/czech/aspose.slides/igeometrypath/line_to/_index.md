---
title: line_to method
second_title: Aspose.Slides pro Python přes .NET API reference
description: 
type: docs
url: /cs/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposeslidespointf}
Přidá čáru na konec cesty


```python
def line_to(self, point):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Konec bod čáry |


## line_to(self, x, y) {#float-float}
Přidá čáru na konec cesty


```python
def line_to(self, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | X-souřadnice koncového bodu čáry |
| y | **float** | Y-souřadnice koncového bodu čáry |


## line_to(self, point, index) {#asposeslidespointf-int}
Přidá čáru na určené místo cesty


```python
def line_to(self, point, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/cs/aspose.slides/pointf) | Konec bod |
| index | **int** | Index segmentu v PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index segmentu je mimo rozsah PathData |


## line_to(self, x, y, index) {#float-float-int}
Přidá čáru na určené místo cesty


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | X-souřadnice bodu |
| y | **float** | Y-souřadnice bodu |
| index | **int** | Index segmentu v PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Index segmentu je mimo rozsah PathData |



### See Also
* třída [`IGeometryPath`](/slides/python-net/cs/aspose.slides/igeometrypath)
* třída [`PointF`](/slides/python-net/cs/aspose.slides/pointf)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)