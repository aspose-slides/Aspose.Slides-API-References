---
title: get_image method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/sectionzoomframe/get_image/
weight: 30
---
## get_image(self) {#}
يُرجع مصغّر الشكل.
            يتم استخدام النوع ShapeThumbnailBounds.Shape كحدود مصغّر الشكل افتراضيًا.

### الإرجاع
مصغّر الشكل.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
يُرجع مصغّر الشكل.

### الإرجاع
مصغّر الشكل أو None في حالة استخدام ShapeThumbnailBounds.Appearance وعدم وجود عناصر مرئية في الشكل.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds) | نوع حدود مصغّر الشكل. |
| scale_x | **float** | مقياس X |
| scale_y | **float** | مقياس Y |

### انظر أيضًا
* فئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* فئة [`SectionZoomFrame`](/slides/python-net/ar/aspose.slides/sectionzoomframe)
* تعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)