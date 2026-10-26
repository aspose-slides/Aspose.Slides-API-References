---
title: quadratic_bezier_to method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/igeometrypath/quadratic_bezier_to/
weight: 60
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
منحنی بیضی درجه دوم را در انتهای مسیر اضافه می‌کند

```python
def quadratic_bezier_to(self, point1, point2):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه جهت‌دار |
| point2 | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه انتهایی |

## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
منحنی بیضی درجه دوم را به مکان مشخصی از مسیر اضافه می‌کند

```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه جهت‌دار |
| point2 | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه انتهایی |
| index | **int** | اندیس بخش در PathData |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اندیس بخش خارج از بازه PathData است |

## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
منحنی بیضی درجه دوم را در انتهای مسیر اضافه می‌کند

```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | مختصات X نقطه جهت‌دار |
| y1 | **float** | مختصات Y نقطه جهت‌دار |
| x2 | **float** | مختصات X نقطه انتهایی |
| y2 | **float** | مختصات Y نقطه انتهایی |

## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
منحنی بیضی درجه دوم را به مکان مشخصی از مسیر اضافه می‌کند

```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | مختصات X نقطه جهت‌دار |
| y1 | **float** | مختصات Y نقطه جهت‌دار |
| x2 | **float** | مختصات X نقطه انتهایی |
| y2 | **float** | مختصات Y نقطه انتهایی |
| index | **int** | اندیس بخش در PathData |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | اندیس بخش خارج از بازه PathData است |

### موارد مرتبط
* class [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath)
* class [`PointF`](/slides/python-net/fa/aspose.slides/pointf)
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)