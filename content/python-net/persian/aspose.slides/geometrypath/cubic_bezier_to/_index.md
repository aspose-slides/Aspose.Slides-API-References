---
title: cubic_bezier_to method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposeslidespointf-asposeslidespointf-asposeslidespointf}
منحنی Bezier مکعب را در انتهای مسیر اضافه می‌کند

```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | اولین نقطه جهت |
| point2 | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | دومین نقطه جهت |
| point3 | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه انتهایی |

## cubic_bezier_to(self, point1, point2, point3, index) {#asposeslidespointf-asposeslidespointf-asposeslidespointf-int}
منحنی Bezier مکعب را در مکان مشخص‌شده مسیر اضافه می‌کند

```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | اولین نقطه جهت |
| point2 | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | دومین نقطه جهت |
| point3 | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه انتهایی |
| index | **int** | شاخص بخش در PathData |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | شاخص بخش خارج از محدوده PathData است |

## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
منحنی Bezier مکعب را در انتهای مسیر اضافه می‌کند

```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x1 | **float** | مختصات X اولین نقطه جهت |
| y1 | **float** | مختصات Y اولین نقطه جهت |
| x2 | **float** | مختصات X دومین نقطه جهت |
| y2 | **float** | مختصات Y دومین نقطه جهت |
| x3 | **float** | مختصات X نقطه انتهایی |
| y3 | **float** | مختصات Y نقطه انتهایی |

## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
منحنی Bezier مکعب را در مکان مشخص‌شده مسیر اضافه می‌کند

```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x1 | **float** | مختصات X اولین نقطه جهت |
| y1 | **float** | مختصات Y اولین نقطه جهت |
| x2 | **float** | مختصات X دومین نقطه جهت |
| y2 | **float** | مختصات Y دومین نقطه جهت |
| x3 | **float** | مختصات X نقطه انتهایی |
| y3 | **float** | مختصات Y نقطه انتهایی |
| index | **int** | شاخص بخش در PathData |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | شاخص بخش خارج از محدوده PathData است |

### موارد مرتبط
* کلاس [`GeometryPath`](/slides/python-net/fa/aspose.slides/geometrypath)
* کلاس [`PointF`](/slides/python-net/fa/aspose.slides/pointf)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)