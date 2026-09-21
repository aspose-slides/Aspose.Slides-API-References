---
title: quadratic_bezier_to method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
منحنی بزیهٔ درجه دوم را در انتهای مسیر اضافه می‌کند


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | نقطه جهت |
| point2 | **aspose.slides.PointF** | نقطه انتها |


## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
منحنی بزیهٔ درجه دوم را به مکان مشخص مسیر اضافه می‌کند


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | نقطه جهت |
| point2 | **aspose.slides.PointF** | نقطه انتها |
| index | **int** | شاخص بخش در PathData |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اندیس بخش خارج از محدوده PathData است |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
منحنی بزیهٔ درجه دوم را در انتهای مسیر اضافه می‌کند


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x1 | **float** | مختصات X نقطه جهت |
| y1 | **float** | مختصات Y نقطه جهت |
| x2 | **float** | مختصات X نقطه انتها |
| y2 | **float** | مختصات Y نقطه انتها |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
منحنی بزیهٔ درجه دوم را به مکان مشخص مسیر اضافه می‌کند


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x1 | **float** | مختصات X نقطه جهت |
| y1 | **float** | مختصات Y نقطه جهت |
| x2 | **float** | مختصات X نقطه انتها |
| y2 | **float** | مختصات Y نقطه انتها |
| index | **int** | شاخص بخش در PathData |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اندیس بخش خارج از محدوده PathData است |



### موارد مرتبط
* کلاس [`GeometryPath`](/slides/python-net/fa/aspose.slides/geometrypath)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)