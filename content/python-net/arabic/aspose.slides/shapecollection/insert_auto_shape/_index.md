---
title: insert_auto_shape method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Creates a new auto shape and inserts it into the shape collection at the specified index,
            applying default template formatting.

### القيمة المرجعة

The newly created [`IAutoShape`](/slides/python-net/ar/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي يتم عنده إدراج الشكل التلقائي الجديد. |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | ال[`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) الخاص بالشكل التلقائي الذي سيتم إدراجه. |
| x | **float** | إحداثي x لإطار الشكل، بوحدات النقاط. |
| y | **float** | إحداثي y لإطار الشكل، بوحدات النقاط. |
| width | **float** | عرض إطار الشكل، بوحدات النقاط. |
| height | **float** | ارتفاع إطار الشكل، بوحدات النقاط. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Creates a new auto shape and inserts it into the shape collection at the specified index,
            optionally initializing it with default template styling.

### القيمة المرجعة

The newly created [`IAutoShape`](/slides/python-net/ar/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي يتم عنده إدراج الشكل التلقائي. |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | ال[`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) الخاص بالشكل التلقائي الذي سيتم إدراجه. |
| x | **float** | إحداثي x لإطار الشكل، بوحدات النقاط. |
| y | **float** | إحداثي y لإطار الشكل، بوحدات النقاط. |
| width | **float** | عرض إطار الشكل، بوحدات النقاط. |
| height | **float** | ارتفاع إطار الشكل، بوحدات النقاط. |
| create_from_template | **bool** | True لتطبيق تنسيق القالب الافتراضي (بما في ذلك اسم غير فارغ، نمط بسيط، ونص متوسط); <br/><br/>            false لإنشاء الشكل مع تعيين جميع الخصائص إلى القيم الافتراضية الخاصة بها. |



### انظر أيضًا
* فئة [`IAutoShape`](/slides/python-net/ar/aspose.slides/iautoshape)
* فئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* تعداد [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)