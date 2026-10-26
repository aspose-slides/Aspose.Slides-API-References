---
title: quadratic_bezier_to method
second_title: راهنمای API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
یک منحنی بزیه درجه دوم در انتهای مسیر اضافه می‌کند


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه جهت |
| point2 | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه انتهایی |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
یک منحنی بزیه درجه دوم را به مکان مشخص‌شده در مسیر اضافه می‌کند


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه جهت |
| point2 | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه انتهایی |
| index | **int** | اندیس قطعه در PathData |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اندیس قطعه خارج از محدوده PathData است |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
یک منحنی بزیه درجه دوم در انتهای مسیر اضافه می‌کند


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x1 | **float** | مختصات X نقطه جهت |
| y1 | **float** | مختصات Y نقطه جهت |
| x2 | **float** | مختصات X نقطه انتهایی |
| y2 | **float** | مختصات Y نقطه انتهایی |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
یک منحنی بزیه درجه دوم را به مکان مشخص‌شده در مسیر اضافه می‌کند


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x1 | **float** | مختصات X نقطه جهت |
| y1 | **float** | مختصات Y نقطه جهت |
| x2 | **float** | مختصات X نقطه انتهایی |
| y2 | **float** | مختصات Y نقطه انتهایی |
| index | **int** | اندیس قطعه در PathData |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اندیس قطعه خارج از محدوده PathData است |



### موارد مرتبط
* کلاس [`GeometryPath`](/slides/python-net/fa/aspose.slides/geometrypath)
* کلاس [`PointF`](/slides/python-net/fa/aspose.slides/pointf)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)