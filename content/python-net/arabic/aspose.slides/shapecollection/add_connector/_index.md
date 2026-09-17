---
title: add_connector method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
ينشئ شكل موصل جديد مع تنسيق القالب الافتراضي ويضيفه إلى نهاية مجموعة الأشكال.

### القيمة المرجعة

العنصر [`IConnector`](/slides/python-net/ar/aspose.slides/iconnector) الذي تم إنشاؤه حديثًا.



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | الـ[`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) للموصل الذي سيتم إضافته. |
| x | **float** | الإحداثي س لإطار الموصل، بوحدة النقاط. |
| y | **float** | الإحداثي ص لإطار الموصل، بوحدة النقاط. |
| width | **float** | عرض إطار الموصل، بوحدة النقاط. |
| height | **float** | ارتفاع إطار الموصل، بوحدة النقاط. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
ينشئ شكل موصل جديد ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تطبيق تنسيق القالب الافتراضي.

### القيمة المرجعة

العنصر [`IConnector`](/slides/python-net/ar/aspose.slides/iconnector) الذي تم إنشاؤه حديثًا.



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | الـ[`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) للموصل الذي سيتم إنشاؤه. |
| x | **float** | الإحداثي س لإطار الموصل، بوحدة النقاط. |
| y | **float** | الإحداثي ص لإطار الموصل، بوحدة النقاط. |
| width | **float** | عرض إطار الموصل، بوحدة النقاط. |
| height | **float** | ارتفاع إطار الموصل، بوحدة النقاط. |
| create_from_template | **bool** | True لتطبيق تنسيق القالب الافتراضي (اسم غير فارغ، نمط بسيط)؛ <br/><br/>false لإنشاء الموصل بقيم الخصائص الافتراضية. |



### انظر أيضًا
* فئة [`IConnector`](/slides/python-net/ar/aspose.slides/iconnector)
* فئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* تعداد [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)