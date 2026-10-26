---
title: contains method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
مشخص می‌کند که آیا نقطهٔ مشخص‌شده در داخل این مستطیل قرار دارد یا خیر.

### بازگشت

`True` اگر نقطه در داخل این مستطیل باشد؛ در غیر این‌صورت، `False`.



```python
def contains(self, point):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/fa/aspose.slides/point) | نقطهٔ آزمون. هر شیئی که دارای ویژگی‌های `x` و `y` باشد، پذیرفته می‌شود. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **TypeError** | تعداد آرگومان‌ها نادرست است. |


## contains(self, rect) {#rectangle}
مشخص می‌کند که آیا ناحیهٔ مستطیلی که توسط `rect` نمایان شده به طور کامل در داخل این مستطیل قرار دارد یا خیر.

### بازگشت

`True` اگر ناحیهٔ مستطیلی که توسط `rect` نمایان شده به طور کامل در داخل این مستطیل باشد؛ در غیر این‌صورت، `False`.



```python
def contains(self, rect):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/fa/aspose.slides/rectangle) | مستطیل آزمون. هر شیئی که دارای ویژگی‌های `x`، `y`، `width` و `height` باشد، پذیرفته می‌شود. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **TypeError** | تعداد آرگومان‌ها نادرست است. |


## contains(self, x, y) {#int-int}
مشخص می‌کند که آیا نقطهٔ مشخص‌شده در داخل این مستطیل قرار دارد یا خیر.

### بازگشت

`True` اگر نقطهٔ تعریف‌شده توسط `x` و `y` در داخل این مستطیل باشد؛ در غیر این‌صورت، `False`.



```python
def contains(self, x, y):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **int** | مختصات x نقطهٔ آزمون. |
| y | **int** | مختصات y نقطهٔ آزمون. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **TypeError** | تعداد آرگومان‌ها نادرست است. |



### موارد مرتبط
* کلاس [`Point`](/slides/python-net/fa/aspose.slides/point)
* کلاس [`Rectangle`](/slides/python-net/fa/aspose.slides/rectangle)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)