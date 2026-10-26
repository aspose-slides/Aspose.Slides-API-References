---
title: get_image method
second_title: Aspose.Slides للغة بايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.smartart/smartartshape/get_image/
weight: 50
---
## get_image(self) {#}
يرجع صورة مصغرة للشكل.
            يتم استخدام نوع حدود صورة مصغرة للشكل ShapeThumbnailBounds.Shape افتراضيًا.

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


| المعاملات | النوع | الوصف |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds) | نوع حدود صورة مصغرة للشكل. |
| scale_x | **float** | مقياس X |
| scale_y | **float** | مقياس Y |



### انظر أيضًا
* فئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* تعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* فئة [`SmartArtShape`](/slides/python-net/ar/aspose.slides.smartart/smartartshape)
* وحدة [`aspose.slides.smartart`](/slides/python-net/ar/aspose.slides.smartart)
* مكتبة [`Aspose.Slides`](/slides/python-net)