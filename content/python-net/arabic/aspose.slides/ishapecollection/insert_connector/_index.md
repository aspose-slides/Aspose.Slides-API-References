---
title: insert_connector method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
ينشئ شكل موصل جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي.

### القيمة المرجعة

الـ [`IConnector`](/slides/python-net/ar/aspose.slides/iconnector) الذي تم إنشاؤه حديثًا.



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| معامل | نوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي سيتم إدراج شكل الموصل عنده. |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | الـ [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) لشكل الموصل الذي سيتم إدراجه. |
| x | **float** | الإحداثي السيني لإطار الموصل، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار الموصل، بالنقاط. |
| width | **float** | عرض إطار الموصل، بالنقاط. |
| height | **float** | ارتفاع إطار الموصل، بالنقاط. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
ينشئ شكل موصل جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد، مع إمكانية تطبيق تنسيق القالب الافتراضي.

### القيمة المرجعة

الـ [`IConnector`](/slides/python-net/ar/aspose.slides/iconnector) الذي تم إنشاؤه حديثًا.



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| معامل | نوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي سيتم إدراج شكل الموصل عنده. |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | الـ [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) لشكل الموصل الذي سيتم إدراجه. |
| x | **float** | الإحداثي السيني لإطار الموصل، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار الموصل، بالنقاط. |
| width | **float** | عرض إطار الموصل، بالنقاط. |
| height | **float** | ارتفاع إطار الموصل، بالنقاط. |
| create_from_template | **bool** | True لتطبيق تنسيق القالب الافتراضي (اسم غير فارغ، نمط بسيط);<br/><br/>false لإنشاء الموصل بقيم الخصائص الافتراضية. |



### انظر أيضًا
* فئة [`IConnector`](/slides/python-net/ar/aspose.slides/iconnector)
* فئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* تعداد [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)