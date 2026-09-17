---
title: line_to method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposepydrawingpointf}
يضيف خطًا إلى نهاية المسار


```python
def line_to(self, point):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| point | **aspose.slides.PointF** | نقطة النهاية للخط |


## line_to(self, x, y) {#float-float}
يضيف خطًا إلى نهاية المسار


```python
def line_to(self, x, y):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| x | **float** | الإحداثي X لنقطة النهاية للخط |
| y | **float** | الإحداثي Y لنقطة النهاية للخط |


## line_to(self, point, index) {#asposepydrawingpointf-int}
يضيف خطًا إلى الموضع المحدد في المسار


```python
def line_to(self, point, index):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| point | **aspose.slides.PointF** | نقطة النهاية |
| index | **int** | فهرس الجزء في PathData |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس الجزء خارج نطاق PathData |


## line_to(self, x, y, index) {#float-float-int}
يضيف خطًا إلى الموضع المحدد في المسار


```python
def line_to(self, x, y, index):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| x | **float** | الإحداثي X للنقطة |
| y | **float** | الإحداثي Y للنقطة |
| index | **int** | فهرس الجزء في PathData |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس الجزء خارج نطاق PathData |



### انظر أيضًا
* الفئة [`IGeometryPath`](/slides/python-net/ar/aspose.slides/igeometrypath)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)