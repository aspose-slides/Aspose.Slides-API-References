---
title: get_image method
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/legacydiagram/get_image/
weight: 50
---
## get_image(self) {#}
يُعيد صورة مصغرة للشكل.
            يُستخدم نوع حدود صورة مصغرة للشكل ShapeThumbnailBounds.Shape افتراضيًا.

### القيمة المرجعة

صورة مصغرة للشكل.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
يُعيد صورة مصغرة للشكل.

### القيمة المرجعة

صورة مصغرة للشكل أو None في حالة استخدام ShapeThumbnailBounds.Appearance ولا يحتوي الشكل على عناصر مرئية.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds) | نوع حدود صورة مصغرة للشكل. |
| scale_x | **float** | مقياس X |
| scale_y | **float** | مقياس Y |



### انظر أيضاً
* class [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* class [`LegacyDiagram`](/slides/python-net/ar/aspose.slides/legacydiagram)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)