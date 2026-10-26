---
title: contains method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا المستطيل.

### القيمة المرجعة

`True` إذا كانت النقطة موجودة داخل هذا المستطيل؛ وإلا `False`.



```python
def contains(self, point):
    ...
```


| معامل | نوع | وصف |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/ar/aspose.slides/point) | النقطة للاختبار. أي كائن يحتوي على خاصيتي `x` و `y` مقبول. |

### الاستثناءات

| استثناء | وصف |
| :- | :- |
| **TypeError** | عدد غير صحيح من الوسائط. |


## contains(self, rect) {#rectangle}
يحدد ما إذا كانت المنطقة المستطيلة الممثلة بـ `rect` موجودة بالكامل داخل هذا المستطيل.

### القيمة المرجعة

`True` إذا كانت المنطقة المستطيلة الممثلة بـ `rect` موجودة بالكامل داخل هذا المستطيل؛ وإلا `False`.



```python
def contains(self, rect):
    ...
```


| معامل | نوع | وصف |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/ar/aspose.slides/rectangle) | المستطيل للاختبار. أي كائن يحتوي على خصائص `x` و `y` و `width` و `height` مقبول. |

### الاستثناءات

| استثناء | وصف |
| :- | :- |
| **TypeError** | عدد غير صحيح من الوسائط. |


## contains(self, x, y) {#int-int}
يحدد ما إذا كانت النقطة المحددة موجودة داخل هذا المستطيل.

### القيمة المرجعة

`True` إذا كانت النقطة المعرفة بـ `x` و `y` موجودة داخل هذا المستطيل؛ وإلا `False`.



```python
def contains(self, x, y):
    ...
```


| معامل | نوع | وصف |
| :- | :- | :- |
| x | **int** | إحداثي x للنقطة للاختبار. |
| y | **int** | إحداثي y للنقطة للاختبار. |

### الاستثناءات

| استثناء | وصف |
| :- | :- |
| **TypeError** | عدد غير صحيح من الوسائط. |



### انظر أيضًا
* فئة [`Point`](/slides/python-net/ar/aspose.slides/point)
* فئة [`Rectangle`](/slides/python-net/ar/aspose.slides/rectangle)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)