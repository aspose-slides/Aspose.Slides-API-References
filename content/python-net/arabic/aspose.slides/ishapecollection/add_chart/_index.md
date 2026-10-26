---
title: add_chart method
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
ينشئ مخططًا جديدًا، ويُهيئه ببيانات وإعدادات سلسلة عينة، ويضيفه إلى نهاية مجموعة الأشكال.

### القيمة المرجعة
العنصر المُنشأ حديثًا [`IChart`](/slides/python-net/ar/aspose.slides.charts/ichart).

```python
def add_chart(self, type, x, y, width, height):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype) | نوع المخطط الذي سيتم إضافته. |
| x | **float** | الإحداثي س للمخطط الجديد، بوحدات النقاط. |
| y | **float** | الإحداثي ص للمخطط الجديد، بوحدات النقاط. |
| width | **float** | عرض المخطط، بوحدات النقاط. |
| height | **float** | ارتفاع المخطط، بوحدات النقاط. |

## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
ينشئ مخططًا جديدًا، ويُهيئه ببيانات وإعدادات سلسلة عينة، ويضيفه إلى نهاية مجموعة الأشكال.

### القيمة المرجعة
العنصر المُنشأ حديثًا [`IChart`](/slides/python-net/ar/aspose.slides.charts/ichart).

```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype) | نوع المخطط الذي سيتم إضافته. |
| x | **float** | الإحداثي س للمخطط الجديد، بوحدات النقاط. |
| y | **float** | الإحداثي ص للمخطط الجديد، بوحدات النقاط. |
| width | **float** | عرض المخطط، بوحدات النقاط. |
| height | **float** | ارتفاع المخطط، بوحدات النقاط. |
| init_with_sample | **bool** | صحيحة لتهيئة المخطط الجديد ببيانات وإعدادات سلسلة عينة؛ <br/><br/>            خاطئة لإنشاء المخطط بدون سلاسل وإعدادات بسيطة فقط، مما يجعل الإنشاء أسرع. |

### انظر أيضًا
* enumeration [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype)
* فئة [`IChart`](/slides/python-net/ar/aspose.slides.charts/ichart)
* فئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)