---
title: get_image method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/zoomobject/get_image/
weight: 30
---
## get_image(self) {#}
يرجع صورة مصغرة للشكل.
            يتم استخدام نوع حدود الصورة المصغرة ShapeThumbnailBounds.Shape بشكل افتراضي.

### إرجاع

صورة مصغرة للشكل.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
يرجع صورة مصغرة للشكل.

### إرجاع

صورة مصغرة للشكل أو لا شيء (None) في حالة استخدام ShapeThumbnailBounds.Appearance وعدم وجود عناصر مرئية للشكل.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| معامل | نوع | وصف |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds) | نوع حدود الصورة المصغرة لل شكل. |
| scale_x | **float** | مقياس X |
| scale_y | **float** | مقياس Y |



### انظر أيضًا
* فئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* تعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* فئة [`ZoomObject`](/slides/python-net/ar/aspose.slides/zoomobject)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)