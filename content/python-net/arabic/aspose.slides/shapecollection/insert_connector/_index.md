---
title: insert_connector method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
ينشئ شكل موصل جديد ويضيفه إلى مجموعة الأشكال في الفهرس المحدد،
            مع تطبيق نمط القالب الافتراضي.

### الإرجاع

الكائن الجديد [`IConnector`](/slides/python-net/ar/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي سيتم إدراج شكل الموصل عنده. |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | الـ [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) لشكل الموصل المراد إدراجه. |
| x | **float** | إحداثي x لإطار الموصل، بالنقاط. |
| y | **float** | إحداثي y لإطار الموصل، بالنقاط. |
| width | **float** | عرض إطار الموصل، بالنقاط. |
| height | **float** | ارتفاع إطار الموصل، بالنقاط. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
ينشئ شكل موصل جديد ويضيفه إلى مجموعة الأشكال في الفهرس المحدد،
            مع إمكانية تطبيق نمط القالب الافتراضي.

### الإرجاع

الكائن الجديد [`IConnector`](/slides/python-net/ar/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي سيتم إدراج شكل الموصل عنده. |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | الـ [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) لشكل الموصل المراد إدراجه. |
| x | **float** | إحداثي x لإطار الموصل، بالنقاط. |
| y | **float** | إحداثي y لإطار الموصل، بالنقاط. |
| width | **float** | عرض إطار الموصل، بالنقاط. |
| height | **float** | ارتفاع إطار الموصل، بالنقاط. |
| create_from_template | **bool** | True لتطبيق نمط القالب الافتراضي (اسم غير فارغ، نمط بسيط);<br/><br/>false لإنشاء الموصل بقيم الخصائص الافتراضية. |



### انظر أيضًا
* فئة [`IConnector`](/slides/python-net/ar/aspose.slides/iconnector)
* فئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* تعداد [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)