---
title: add_auto_shape method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
ينشئ شكلاً تلقائيًا جديدًا بتنسيق افتراضي ويضيفه إلى نهاية مجموعة الأشكال.

### الإرجاع

العنصر [`IAutoShape`](/slides/python-net/ar/aspose.slides/iautoshape) الذي تم إنشاؤه حديثًا.



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | الـ [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) للشكل التلقائي الذي سيتم إضافته. |
| x | **float** | الإحداثي x لإطار الشكل، بالنقاط. |
| y | **float** | الإحداثي y لإطار الشكل، بالنقاط. |
| width | **float** | عرض إطار الشكل، بالنقاط. |
| height | **float** | ارتفاع إطار الشكل، بالنقاط. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
ينشئ شكلاً تلقائيًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال، ويمكنه اختياريًا تهيئته بتنسيق القالب الافتراضي.

### الإرجاع

العنصر [`IAutoShape`](/slides/python-net/ar/aspose.slides/iautoshape) الذي تم إنشاؤه حديثًا.



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | الـ [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) للشكل التلقائي الذي سيتم إضافته. |
| x | **float** | الإحداثي x لإطار الشكل، بالنقاط. |
| y | **float** | الإحداثي y لإطار الشكل، بالنقاط. |
| width | **float** | عرض إطار الشكل، بالنقاط. |
| height | **float** | ارتفاع إطار الشكل، بالنقاط. |
| create_from_template | **bool** | True لتطبيق تنسيق القالب الافتراضي (نمط بسيط، نص مركزي، واسم غير فارغ)<br/><br/>            على الشكل الجديد؛ false لإنشاء الشكل مع تعيين جميع الخصائص إلى القيم الافتراضية لها. |



### راجع أيضًا
* فئة [`IAutoShape`](/slides/python-net/ar/aspose.slides/iautoshape)
* فئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* تعداد [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)