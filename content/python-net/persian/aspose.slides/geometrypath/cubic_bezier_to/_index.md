---
title: cubic_bezier_to method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
منحنی Bezier درجه‌سه را به انتهای مسیر اضافه می‌کند


```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | نقطه جهت‌دار اول |
| point2 | **aspose.slides.PointF** | نقطه جهت‌دار دوم |
| point3 | **aspose.slides.PointF** | نقطه انتهایی |


## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
منحنی Bezier درجه‌سه را به مکان مشخص شده در مسیر اضافه می‌کند


```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | نقطه جهت‌دار اول |
| point2 | **aspose.slides.PointF** | نقطه جهت‌دار دوم |
| point3 | **aspose.slides.PointF** | نقطه انتهایی |
| index | **int** | اندیس بخش در PathData |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اندیس بخش خارج از محدوده PathData است |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
منحنی Bezier درجه‌سه را به انتهای مسیر اضافه می‌کند


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x1 | **float** | مختصات X نقطه جهت‌دار اول |
| y1 | **float** | مختصات Y نقطه جهت‌دار اول |
| x2 | **float** | مختصات X نقطه جهت‌دار دوم |
| y2 | **float** | مختصات Y نقطه جهت‌دار دوم |
| x3 | **float** | مختصات X نقطه انتهایی |
| y3 | **float** | مختصات Y نقطه انتهایی |


## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
منحنی Bezier درجه‌سه را به مکان مشخص شده در مسیر اضافه می‌کند


```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x1 | **float** | مختصات X نقطه جهت‌دار اول |
| y1 | **float** | مختصات Y نقطه جهت‌دار اول |
| x2 | **float** | مختصات X نقطه جهت‌دار دوم |
| y2 | **float** | مختصات Y نقطه جهت‌دار دوم |
| x3 | **float** | مختصات X نقطه انتهایی |
| y3 | **float** | مختصات Y نقطه انتهایی |
| index | **int** | اندیس بخش در PathData |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اندیس بخش خارج از محدوده PathData است |



### موارد مرتبط
* کلاس [`GeometryPath`](/slides/python-net/fa/aspose.slides/geometrypath)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)