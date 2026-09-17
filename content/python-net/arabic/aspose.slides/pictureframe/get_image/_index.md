---
title: get_image method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/pictureframe/get_image/
weight: 50
---
## get_image(self) {#}
تُعيد صورة مصغرة للشكل.
            يتم استخدام نوع حدود الصورة المصغرة ShapeThumbnailBounds.Shape بشكل افتراضي.

### القيمة المرجعة
صورة مصغرة للشكل.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
تُعيد صورة مصغرة للشكل.

### القيمة المرجعة
صورة مصغرة للشكل أو None في حال تم استخدام ShapeThumbnailBounds.Appearance ولا يحتوي الشكل على عناصر مرئية.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds) | نوع حدود الصورة المصغرة للشكل. |
| scale_x | **float** | مقياس X |
| scale_y | **float** | مقياس Y |

### انظر أيضًا
* الفئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* الفئة [`PictureFrame`](/slides/python-net/ar/aspose.slides/pictureframe)
* التعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)