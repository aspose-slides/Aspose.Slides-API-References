---
title: get_image method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/graphicalobject/get_image/
weight: 30
---
## get_image(self) {#}
يرجع صورة مصغرة للشكل. يتم استخدام نوع حدود صورة مصغرة للشكل ShapeThumbnailBounds.Shape بشكل افتراضي.

### القيمة المرجعة

صورة مصغرة للشكل.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
يرجع صورة مصغرة للشكل.

### القيمة المرجعة

صورة مصغرة للشكل أو None في حالة استخدام ShapeThumbnailBounds.Appearance وعدم وجود عناصر مرئية للشكل.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds) | نوع حدود صورة مصغرة للشكل. |
| scale_x | **float** | مقياس X |
| scale_y | **float** | مقياس Y |



### انظر أيضًا
* فئة [`GraphicalObject`](/slides/python-net/ar/aspose.slides/graphicalobject)
* فئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* تعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)