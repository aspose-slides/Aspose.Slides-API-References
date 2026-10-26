---
title: insert_auto_shape method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
ينشئ شكلًا تلقائيًا جديدًا ويدخله في مجموعة الأشكال عند الفهرس المحدد، مع تطبيق تنسيق القالب الافتراضي.

### القيمة المرجعة

العنصر الذي تم إنشاؤه حديثًا [`IAutoShape`](/slides/python-net/ar/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | المؤشر الصفري الذي يتم عنده إدراج الشكل التلقائي الجديد. |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | الـ[`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) الخاص بالشكل التلقائي الذي سيتم إدراجه. |
| x | **float** | الإحداثي السيني لإطار الشكل، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار الشكل، بالنقاط. |
| width | **float** | عرض إطار الشكل، بالنقاط. |
| height | **float** | ارتفاع إطار الشكل، بالنقاط. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
ينشئ شكلًا تلقائيًا جديدًا ويدخله في مجموعة الأشكال عند الفهرس المحدد، اختياريًا يهيئه بنمط القالب الافتراضي.

### القيمة المرجعة

العنصر الذي تم إنشاؤه حديثًا [`IAutoShape`](/slides/python-net/ar/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | المؤشر الصفري الذي يتم عنده إدراج الشكل التلقائي. |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | الـ[`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) الخاص بالشكل التلقائي الذي سيتم إدراجه. |
| x | **float** | الإحداثي السيني لإطار الشكل، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار الشكل، بالنقاط. |
| width | **float** | عرض إطار الشكل، بالنقاط. |
| height | **float** | ارتفاع إطار الشكل، بالنقاط. |
| create_from_template | **bool** | True لتطبيق تنسيق القالب الافتراضي (بما في ذلك اسم غير فارغ، نمط بسيط، ونص متوسط); <br/><br/>false لإنشاء الشكل بجميع الخصائص مضبوطة على القيم الافتراضية. |



### انظر أيضًا
* الفئة [`IAutoShape`](/slides/python-net/ar/aspose.slides/iautoshape)
* الفئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* التعداد [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)