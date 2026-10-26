---
title: add_auto_shape method
second_title: Aspose.Slides ل‏Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
يقوم بإنشاء شكل تلقائي جديد بالتنسيق الافتراضي ويضيفه إلى نهاية مجموعة الأشكال.

### الإرجاع

العنصر [`IAutoShape`](/slides/python-net/ar/aspose.slides/iautoshape) الذي تم إنشاؤه حديثًا.



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) of the auto shape to add. |
| x | **float** | The x-coordinate of the shape’s frame, in points. |
| y | **float** | The y-coordinate of the shape’s frame, in points. |
| width | **float** | The width of the shape’s frame, in points. |
| height | **float** | The height of the shape’s frame, in points. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
يقوم بإنشاء شكل تلقائي جديد ويضيفه إلى نهاية مجموعة الأشكال، مع إمكانية تهيئته بتنسيق القالب الافتراضي.

### الإرجاع

العنصر [`IAutoShape`](/slides/python-net/ar/aspose.slides/iautoshape) الذي تم إنشاؤه حديثًا.



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) | The [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype) of the auto shape to add. |
| x | **float** | The x-coordinate of the shape’s frame, in points. |
| y | **float** | The y-coordinate of the shape’s frame, in points. |
| width | **float** | The width of the shape’s frame, in points. |
| height | **float** | The height of the shape’s frame, in points. |
| create_from_template | **bool** | True لتطبيق تنسيق القالب الافتراضي (نمط بسيط، نص متموضع في الوسط، واسم غير فارغ)<br/><br/> على الشكل الجديد؛ false لإنشاء الشكل مع تعيين جميع الخصائص إلى قيمها الافتراضية. |



### انظر أيضًا
* الفئة [`IAutoShape`](/slides/python-net/ar/aspose.slides/iautoshape)
* الفئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* التعداد [`ShapeType`](/slides/python-net/ar/aspose.slides/shapetype)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)