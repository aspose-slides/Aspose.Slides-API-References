---
title: get_image method
second_title: Aspose.Slides لـ Python عبر مرجع .NET API
description: 
type: docs
url: /ar/aspose.slides/autoshape/get_image/
weight: 60
---
## get_image(self) {#}
يرجع صورة مصغرة للشكل.
            يُستخدم نوع حدود صورة مصغرة للشكل ShapeThumbnailBounds.Shape بشكل افتراضي.

### الإرجاع

صورة مصغرة للشكل.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
يرجع صورة مصغرة للشكل.

### الإرجاع

صورة مصغرة للشكل أو None في الحالة التي يُستخدم فيها ShapeThumbnailBounds.Appearance ولا يحتوي الشكل على عناصر مرئية.

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
* الفئة [`AutoShape`](/slides/python-net/ar/aspose.slides/autoshape)
* الفئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* التعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)