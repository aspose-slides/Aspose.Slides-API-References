---
title: get_image method
second_title: مرجع Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/groupshape/get_image/
weight: 30
---
## get_image(self) {#}
إرجاع صورة مصغرة للشكل.  
ShapeThumbnailBounds.Shape shape thumbnail bounds type يُستخدم بشكلٍ افتراضي.

### Returns
صورة مصغرة للشكل.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
إرجاع صورة مصغرة للشكل.

### Returns
صورة مصغرة للشكل أو None في حالة استخدام ShapeThumbnailBounds.Appearance وعدم وجود عناصر مرئية للشكل.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds) | نوع حدود الصورة المصغرة للشكل. |
| scale_x | **float** | مقياس X |
| scale_y | **float** | مقياس Y |

### See Also
* فئة [`GroupShape`](/slides/python-net/ar/aspose.slides/groupshape)
* فئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* تعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)