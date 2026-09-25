---
title: contains method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
تعیین می‌کند آیا نقطهٔ مشخص‌شده در داخل این مستطیل قرار دارد یا خیر.

### بازگرداندن

`True` اگر نقطه در داخل این مستطیل قرار داشته باشد؛ در غیر این صورت `False`.



```python
def contains(self, point):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/fa/aspose.slides/pointf) | نقطه برای آزمون. هر شیئی که دارای ویژگی‌های `x` و `y` باشد پذیرفته می‌شود. |

### استثناها

| Exception | Description |
| :- | :- |
| **TypeError** | تعداد نادرست آرگومان‌ها. |


## contains(self, rect) {#rectanglef}
تعیین می‌کند آیا ناحیهٔ مستطیلی که توسط `rect` نشان داده شده به‌طور کامل در داخل این مستطیل قرار دارد یا خیر.

### بازگرداندن

`True` اگر ناحیهٔ مستطیلی که توسط `rect` نشان داده شده به‌طور کامل در داخل این مستطیل قرار داشته باشد؛ در غیر این صورت `False`.



```python
def contains(self, rect):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef) | مستطیل برای آزمون. هر شیئی که دارای ویژگی‌های `x`، `y`، `width` و `height` باشد پذیرفته می‌شود. |

### استثناها

| Exception | Description |
| :- | :- |
| **TypeError** | تعداد نادرست آرگومان‌ها. |


## contains(self, x, y) {#float-float}
تعیین می‌کند آیا نقطهٔ مشخص‌شده در داخل این مستطیل قرار دارد یا خیر.

### بازگرداندن

`True` اگر نقطهٔ تعریف‌شده توسط `x` و `y` در داخل این مستطیل قرار داشته باشد؛ در غیر این صورت `False`.



```python
def contains(self, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | مختصات x نقطه برای آزمون. |
| y | **float** | مختصات y نقطه برای آزمون. |

### استثناها

| Exception | Description |
| :- | :- |
| **TypeError** | تعداد نادرست آرگومان‌ها. |



### موارد مرتبط
* کلاس [`PointF`](/slides/python-net/fa/aspose.slides/pointf)
* کلاس [`RectangleF`](/slides/python-net/fa/aspose.slides/rectanglef)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)