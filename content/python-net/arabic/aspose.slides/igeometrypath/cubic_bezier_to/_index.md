---
title: cubic_bezier_to method
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/igeometrypath/cubic_bezier_to/
weight: 30
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
يضيف منحنى بيزيه من الدرجة الثالثة في نهاية المسار


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | نقطة الاتجاه الأولى |
| point2 | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | نقطة الاتجاه الثانية |
| point3 | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | نقطة النهاية |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
يضيف منحنى بيزيه من الدرجة الثالثة إلى الموضع المحدد في المسار


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | نقطة الاتجاه الأولى |
| point2 | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | نقطة الاتجاه الثانية |
| point3 | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | نقطة النهاية |
| index | **int** | فهرس الجزء في PathData |

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس الجزء خارج نطاق PathData |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
يضيف منحنى بيزيه من الدرجة الثالثة في نهاية المسار


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| x1 | **float** | إحداثي X لنقطة الاتجاه الأولى |
| y1 | **float** | إحداثي Y لنقطة الاتجاه الأولى |
| x2 | **float** | إحداثي X لنقطة الاتجاه الثانية |
| y2 | **float** | إحداثي Y لنقطة الاتجاه الثانية |
| x3 | **float** | إحداثي X لنقطة النهاية |
| y3 | **float** | إحداثي Y لنقطة النهاية |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
يضيف منحنى بيزيه من الدرجة الثالثة إلى الموضع المحدد في المسار


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| x1 | **float** | إحداثي X لنقطة الاتجاه الأولى |
| y1 | **float** | إحداثي Y لنقطة الاتجاه الأولى |
| x2 | **float** | إحداثي X لنقطة الاتجاه الثانية |
| y2 | **float** | إحداثي Y لنقطة الاتجاه الثانية |
| x3 | **float** | إحداثي X لنقطة النهاية |
| y3 | **float** | إحداثي Y لنقطة النهاية |
| index | **int** | فهرس الجزء في PathData |

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس الجزء خارج نطاق PathData |



### انظر أيضًا
* الفئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* الفئة [`PointF`](/slides/python-net/ar/aspose.slides/pointf)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)