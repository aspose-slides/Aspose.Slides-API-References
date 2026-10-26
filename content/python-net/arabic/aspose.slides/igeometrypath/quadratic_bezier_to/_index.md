---
title: quadratic_bezier_to method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
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
يضيف منحنى بيزيه تربيعي إلى المكان المحدد في المسار


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | نقطة الاتجاه |
| point2 | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | نقطة النهاية |
| index | **int** | فهرس القطعة في PathData |

### الاستثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس القطعة خارج نطاق PathData |


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
يضيف منحنى بيزيه تربيعي إلى المكان المحدد في المسار


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
| index | **int** | فهرس القطعة في PathData |

### الاستثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس القطعة خارج نطاق PathData |



### انظر أيضًا
* فئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* فئة [`PointF`](/slides/python-net/ar/aspose.slides/pointf)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)