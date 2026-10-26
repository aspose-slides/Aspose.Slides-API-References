---
title: from_name method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
ينشئ لونًا من الاسم المحدد للون معرف مسبقًا.<br/>البحث غير حساس لحالة الأحرف ويتجاهل الشرطات السفلية والمسافات: `"LightBlue"`، `"lightblue"` و `"light_blue"` جميعها تُحول إلى `Color.light_blue`. انظر صفحة الفئة [`Color`](/slides/python-net/ar/aspose.slides/color) للقائمة الخاصة بالألوان المعرفة مسبقًا.

### القيمة المرجعة

اللون المسمى.



```python
@staticmethod
def from_name(name):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| name | **str** | سلسلة تمثل اسم لون معرف مسبقًا. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **ValueError** | الاسم ليس اسمًا لأحد الألوان المعرفة مسبقًا. |
| **TypeError** | الاسم ليس سلسلة. |



### انظر أيضًا
* فئة [`Color`](/slides/python-net/ar/aspose.slides/color)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)