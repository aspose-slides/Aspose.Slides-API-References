---
title: line_to method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposepydrawingpointf}
خطی را به انتهای مسیر اضافه می‌کند


```python
def line_to(self, point):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point | **aspose.slides.PointF** | نقطه انتهایی خط |


## line_to(self, x, y) {#float-float}
خطی را به انتهای مسیر اضافه می‌کند


```python
def line_to(self, x, y):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **float** | مختصات X نقطه انتهایی خط |
| y | **float** | مختصات Y نقطه انتهایی خط |


## line_to(self, point, index) {#asposepydrawingpointf-int}
خطی را به مکان مشخصی در مسیر اضافه می‌کند


```python
def line_to(self, point, index):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point | **aspose.slides.PointF** | نقطه انتهایی |
| index | **int** | شاخص بخش در PathData |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | شاخص بخش خارج از محدوده PathData است |


## line_to(self, x, y, index) {#float-float-int}
خطی را به مکان مشخصی در مسیر اضافه می‌کند


```python
def line_to(self, x, y, index):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **float** | مختصات X نقطه |
| y | **float** | مختصات Y نقطه |
| index | **int** | شاخص بخش در PathData |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | شاخص بخش خارج از محدوده PathData است |



### مراجع مرتبط
* کلاس [`GeometryPath`](/slides/python-net/fa/aspose.slides/geometrypath)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)