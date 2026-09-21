---
title: quadratic_bezier_to method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposepydrawingpointf-asposepydrawingpointf}
منحنی Bezier درجه دوم را به انتهای مسیر اضافه می‌کند

```python
def quadratic_bezier_to(self, point1, point2):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | نقطه جهت |
| point2 | **aspose.slides.PointF** | نقطه انتها |

## quadratic_bezier_to(self, point1, point2, index) {#asposepydrawingpointf-asposepydrawingpointf-int}
منحنی Bezier درجه دوم را به مکان مشخصی از مسیر اضافه می‌کند

```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | نقطه جهت |
| point2 | **aspose.slides.PointF** | نقطه انتها |
| index | **int** | اندیس بخش در PathData |

### استثناها

| استثناء | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اندیس بخش خارج از محدوده PathData است |

## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
منحنی Bezier درجه دوم را به انتهای مسیر اضافه می‌کند

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
منحنی Bezier درجه دوم را به مکان مشخصی از مسیر اضافه می‌کند

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
| index | **int** | اندیس بخش در PathData |

### استثناها

| استثناء | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اندیس بخش خارج از محدوده PathData است |

### موارد مرتبط
* کلاس [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)