---
title: get_image method
second_title: Aspose.Slides للغة Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.charts/chart/get_image/
weight: 40
---
## get_image(self) {#}
إرجاع صورة مصغرة للشكل.
يتم استخدام نوع حدود صورة مصغرة للشكل ShapeThumbnailBounds.Shape افتراضيًا.

### إرجاع

صورة مصغرة لل شكل.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
إرجاع صورة مصغرة للشكل.

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
* الفئة [`Chart`](/slides/python-net/ar/aspose.slides.charts/chart)
* الفئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* التعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* الوحدة [`aspose.slides.charts`](/slides/python-net/ar/aspose.slides.charts)
* المكتبة [`Aspose.Slides`](/slides/python-net)