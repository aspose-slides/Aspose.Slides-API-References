---
title: add_connector method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
إنشاء شكل موصل جديد باستخدام نمط القالب الافتراضي وإضافته إلى نهاية مجموعة الأشكال.

### القيمة المرجعة

العنصر الجديد المُنشأ [`IConnector`](/slides/python-net/ar/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | الـ[`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) للموصل الذي سيتم إضافته. |
| x | **float** | الإحداثي السيني لإطار الموصل، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار الموصل، بالنقاط. |
| width | **float** | عرض إطار الموصل، بالنقاط. |
| height | **float** | ارتفاع إطار الموصل، بالنقاط. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
إنشاء شكل موصل جديد وإضافته إلى نهاية مجموعة الأشكال، مع إمكانية تطبيق نمط القالب الافتراضي.

### القيمة المرجعة

العنصر الجديد المُنشأ [`IConnector`](/slides/python-net/ar/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | الـ[`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) للموصل الذي سيتم إنشائه. |
| x | **float** | الإحداثي السيني لإطار الموصل، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار الموصل، بالنقاط. |
| width | **float** | عرض إطار الموصل، بالنقاط. |
| height | **float** | ارتفاع إطار الموصل، بالنقاط. |
| create_from_template | **bool** | True لتطبيق نمط القالب الافتراضي (اسم غير فارغ، نمط بسيط); <br/><br/> false لإنشاء الموصل بقيم الخصائص الافتراضية. |



### انظر أيضًا
* الفئة [`IConnector`](/slides/python-net/ar/aspose.slides/iconnector)
* الفئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* التعداد [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)