---
title: insert_chart method
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
يقوم بإنشاء مخطط جديد، يهيئه ببيانات وسلسلة عينات وإعدادات، ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

### إرجاع

المُنشئ حديثًا [`IChart`](/slides/python-net/ar/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| معامل | نوع | وصف |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype) | نوع المخطط لإنشائه. |
| x | **float** | إحداثي x للمخطط الجديد، بوحدات النقاط. |
| y | **float** | إحداثي y للمخطط الجديد، بوحدات النقاط. |
| width | **float** | عرض المخطط الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع المخطط الجديد، بوحدات النقاط. |
| index | **int** | الفهرس الذي يبدأ من الصفر والذي تُدرج عنده المخطط الجديد في مجموعة الأشكال. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
يقوم بإنشاء مخطط جديد، يهيئه ببيانات وسلسلة عينات وإعدادات، ويُدرجه في مجموعة الأشكال في الفهرس المحدد.

### إرجاع

المُنشئ حديثًا [`IChart`](/slides/python-net/ar/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| معامل | نوع | وصف |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype) | نوع المخطط لإنشائه. |
| x | **float** | إحداثي x للمخطط الجديد، بوحدات النقاط. |
| y | **float** | إحداثي y للمخطط الجديد، بوحدات النقاط. |
| width | **float** | عرض المخطط الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع المخطط الجديد، بوحدات النقاط. |
| index | **int** | الفهرس الذي يبدأ من الصفر والذي تُدرج عنده المخطط الجديد في مجموعة الأشكال. |
| init_with_sample | **bool** | True لتهيئة المخطط الجديد ببيانات وسلسلة عينات وإعدادات؛ <br/><br/> false لإنشاء المخطط بدون سلاسل ومع إعدادات قليلة فقط، مما يجعل الإنشاء أسرع. |



### انظر أيضًا
* تعداد [`ChartType`](/slides/python-net/ar/aspose.slides.charts/charttype)
* فئة [`IChart`](/slides/python-net/ar/aspose.slides.charts/ichart)
* فئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)