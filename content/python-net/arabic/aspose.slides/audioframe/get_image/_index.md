---
title: get_image method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/audioframe/get_image/
weight: 50
---
## get_image(self) {#}
يرجع صورة مصغرة للشكل.
            ShapeThumbnailBounds.Shape نوع حدود صورة مصغرة للشكل يُستخدم بشكل افتراضي.

### إرجاع

صورة مصغرة للشكل.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
يرجع صورة مصغرة للشكل.

### إرجاع

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
* فئة [`AudioFrame`](/slides/python-net/ar/aspose.slides/audioframe)
* فئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* تعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)