---
title: cubic_bezier_to method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
يضيف منحنى بيزيه مكعّب في نهاية المسار


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | نقطة الاتجاه الأولى |
| point2 | **aspose.slides.PointF** | نقطة الاتجاه الثانية |
| point3 | **aspose.slides.PointF** | نقطة النهاية |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
يضيف منحنى بيزيه مكعّب إلى الموضع المحدد في المسار


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | نقطة الاتجاه الأولى |
| point2 | **aspose.slides.PointF** | نقطة الاتجاه الثانية |
| point3 | **aspose.slides.PointF** | نقطة النهاية |
| index | **int** | فهرس القطعة في PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس القطعة خارج نطاق PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
يضيف منحنى بيزيه مكعّب في نهاية المسار


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | إحداثي X لنقطة الاتجاه الأولى |
| y1 | **float** | إحداثي Y لنقطة الاتجاه الأولى |
| x2 | **float** | إحداثي X لنقطة الاتجاه الثانية |
| y2 | **float** | إحداثي Y لنقطة الاتجاه الثانية |
| x3 | **float** | إحداثي X لنقطة النهاية |
| y3 | **float** | إحداثي Y لنقطة النهاية |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
يضيف منحنى بيزيه مكعّب إلى الموضع المحدد في المسار


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | إحداثي X لنقطة الاتجاه الأولى |
| y1 | **float** | إحداثي Y لنقطة الاتجاه الأولى |
| x2 | **float** | إحداثي X لنقطة الاتجاه الثانية |
| y2 | **float** | إحداثي Y لنقطة الاتجاه الثانية |
| x3 | **float** | إحداثي X لنقطة النهاية |
| y3 | **float** | إحداثي Y لنقطة النهاية |
| index | **int** | فهرس القطعة في PathData |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس القطعة خارج نطاق PathData |



### See Also
* class [`GeometryPath`](/slides/python-net/ar/aspose.slides/geometrypath)
* module [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)