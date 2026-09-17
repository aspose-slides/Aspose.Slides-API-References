---
title: add_group_shape method
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
ينشئ شكلاً مجموعيًا فارغًا جديدًا ويضيفه إلى نهاية مجموعة الأشكال.
            سيتadjust إطار المجموعة تلقائيًا ليتناسب مع أي أشكال تُضاف إليه.

### القيمة المرجعة

The newly created [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape).



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
ينشئ شكلاً مجموعيًا جديدًا، يحول صورة SVG المحددة إلى أشكال منفصلة، ويضيف المجموعة الناتجة إلى نهاية مجموعة الأشكال.

### القيمة المرجعة

The newly created [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape).



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/ar/aspose.slides/isvgimage) | [`ISvgImage`](/slides/python-net/ar/aspose.slides/isvgimage) التي تحتوي على محتوى متجه لتحويله إلى أشكال. |
| x | **float** | إحداثي x لإطار المجموعة، بالنقاط. |
| y | **float** | إحداثي y لإطار المجموعة، بالنقاط. |
| width | **float** | عرض إطار المجموعة، بالنقاط. |
| height | **float** | ارتفاع إطار المجموعة، بالنقاط. |



### انظر أيضًا
* الفئة [`IGroupShape`](/slides/python-net/ar/aspose.slides/igroupshape)
* الفئة [`ISvgImage`](/slides/python-net/ar/aspose.slides/isvgimage)
* الفئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)