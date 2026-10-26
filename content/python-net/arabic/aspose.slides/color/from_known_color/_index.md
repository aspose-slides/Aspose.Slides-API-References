---
title: from_known_color method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
ينشئ لونًا من اللون المُعرّف مسبقًا المحدد.<br/>هذه هي الطريقة الوحيدة للحصول على لون نظام (مثل `KnownColor.CONTROL`): لا يتم الكشف عن ألوان النظام كخصائص `Color` لأن قيمها تعتمد على سمة سطح المكتب، لذا يتم قراءتها من وقت تشغيل المكتبة.

### القيمة المرجعة

اللون الذي تُنشئه هذه الطريقة.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| known_color | **KnownColor** | عنصر من تعداد `KnownColor` (وهو `IntEnum` يعكس .NET `System.Drawing.KnownColor`) أو قيمته الصحيحة. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **ValueError** | القيمة ليست عنصرًا صالحًا في `KnownColor`. |



### أنظر أيضًا
* فئة [`Color`](/slides/python-net/ar/aspose.slides/color)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)