---
title: quadratic_bezier_to method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
يضيف منحنى بيزيه تربيعي في نهاية المسار


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | نقطة الاتجاه |
| point2 | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | نقطة النهاية |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
يضيف منحنى بيزيه تربيعي إلى الموضع المحدد في المسار


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | نقطة الاتجاه |
| point2 | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | نقطة النهاية |
| index | **int** | فهرس الجزء في PathData |

### الاستثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس الجزء خارج نطاق PathData |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
يضيف منحنى بيزيه تربيعي في نهاية المسار


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| المعامل | النوع | الوصف |
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


| المعامل | النوع | الوصف |
| :- | :- | :- |
| x1 | **float** | إحداثي X لنقطة الاتجاه |
| y1 | **float** | إحداثي Y لنقطة الاتجاه |
| x2 | **float** | إحداثي X لنقطة النهاية |
| y2 | **float** | إحداثي Y لنقطة النهاية |
| index | **int** | فهرس الجزء في PathData |

### الاستثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس الجزء خارج نطاق PathData |



### انظر أيضًا
* الفئة [`GeometryPath`](/slides/python-net/ar/aspose.slides/geometrypath)
* الفئة [`PointF`](/slides/python-net/ar/aspose.slides/pointf)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)