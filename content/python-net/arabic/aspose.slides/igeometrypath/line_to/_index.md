---
title: line_to method
second_title: Aspose.Slides للبايثون عبر .NET - مرجع API
description: 
type: docs
url: /ar/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposeslidespointf}
يضيف خطًا إلى نهاية المسار


```python
def line_to(self, point):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | النقطة النهائية للخط |


## line_to(self, x, y) {#float-float}
يضيف خطًا إلى نهاية المسار


```python
def line_to(self, x, y):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| x | **float** | الإحداثي X للنقطة النهائية للخط |
| y | **float** | الإحداثي Y للنقطة النهائية للخط |


## line_to(self, point, index) {#asposeslidespointf-int}
يضيف خطًا إلى المكان المحدد في المسار


```python
def line_to(self, point, index):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/ar/aspose.slides/pointf) | النقطة النهائية |
| index | **int** | فهرس الجزء في PathData |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | فهرس الجزء خارج نطاق PathData |


## line_to(self, x, y, index) {#float-float-int}
يضيف خطًا إلى المكان المحدد في المسار


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
* الفئة [`PointF`](/slides/python-net/ar/aspose.slides/pointf)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)