---
title: line_to method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposeslidespointf}
Adds line to the end of the path

```python
def line_to(self, point):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه انتهای خط |

## line_to(self, x, y) {#float-float}
Adds line to the end of the path

```python
def line_to(self, x, y):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **float** | مختصات X نقطه انتهای خط |
| y | **float** | مختصات Y نقطه انتهای خط |

## line_to(self, point, index) {#asposeslidespointf-int}
Adds line to the specified place of the path

```python
def line_to(self, point, index):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه انتهایی |
| index | **int** | شاخص بخش در PathData |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | شاخص بخش خارج از محدوده PathData است |

## line_to(self, x, y, index) {#float-float-int}
Adds line to the specified place of the path

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

### موارد مرتبط
* کلاس [`IGeometryPath`](/slides/python-net/fa/aspose.slides/igeometrypath)
* کلاس [`PointF`](/slides/python-net/fa/aspose.slides/pointf)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)