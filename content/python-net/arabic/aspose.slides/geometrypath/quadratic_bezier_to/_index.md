---
title: quadratic_bezier_to method
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
يضيف منحنى بيزيه تربيعي في نهاية المسار


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | نقطة الاتجاه |
| point2 | **aspose.slides.PointF** | نقطة النهاية |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
يضيف منحنى بيزيه تربيعي إلى الموضع المحدد في المسار


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | نقطة الاتجاه |
| point2 | **aspose.slides.PointF** | نقطة النهاية |
| index | **int** | فهرس الجزء في PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس الجزء خارج نطاق PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
يضيف منحنى بيزيه تربيعي في نهاية المسار


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | إحداثي X لنقطة الاتجاه |
| y1 | **float** | إحداثي Y لنقطة الاتجاه |
| x2 | **float** | إحداثي X لنقطة النهاية |
| y2 | **float** | إحداثي Y لنقطة النهاية |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
يضيف منحنى بيزيه تربيعي إلى الموضع المحدد في المسار


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | إحداثي X لنقطة الاتجاه |
| y1 | **float** | إحداثي Y لنقطة الاتجاه |
| x2 | **float** | إحداثي X لنقطة النهاية |
| y2 | **float** | إحداثي Y لنقطة النهاية |
| index | **int** | فهرس الجزء في PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس الجزء خارج نطاق PathData |



### See Also
* class [`GeometryPath`](/slides/python-net/ar/aspose.slides/geometrypath)
* module [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)