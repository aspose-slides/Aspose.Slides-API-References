---
title: line_to method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposeslidespointf}
يضيف خطًا إلى نهاية المسار


```python
def line_to(self, point):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | نقطة النهاية للخط |


## line_to(self, x, y) {#float-float}
يضيف خطًا إلى نهاية المسار


```python
def line_to(self, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | الإحداثي X لنقطة النهاية للخط |
| y | **float** | الإحداثي Y لنقطة النهاية للخط |


## line_to(self, point, index) {#asposeslidespointf-int}
يضيف خطًا إلى الموضع المحدد في المسار


```python
def line_to(self, point, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | نقطة النهاية |
| index | **int** | فهرس الجزء في PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس الجزء خارج نطاق PathData |


## line_to(self, x, y, index) {#float-float-int}
يضيف خطًا إلى الموضع المحدد في المسار


```python
def line_to(self, x, y, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | الإحداثي X للنقطة |
| y | **float** | الإحداثي Y للنقطة |
| index | **int** | فهرس الجزء في PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس الجزء خارج نطاق PathData |



### See Also
* class [`GeometryPath`](/slides/python-net/ar/aspose.slides/geometrypath)
* class [`PointF`](/slides/python-net/ar/aspose.slides/pointf)
* module [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)