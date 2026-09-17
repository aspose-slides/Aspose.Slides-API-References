---
title: get_image method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/zoomframe/get_image/
weight: 30
---
## get_image(self) {#}
يرجع صورة مصغرة للشكل.  
            يتم استخدام نوع حدود الصورة المصغرة للشكل (ShapeThumbnailBounds.Shape) بشكل افتراضي.

### القيمة المرجعة

صورة مصغرة للشكل.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
يرجع صورة مصغرة للشكل.

### القيمة المرجعة

صورة مصغرة للشكل أو None في حال تم استخدام ShapeThumbnailBounds.Appearance ولا يحتوي الشكل على عناصر مرئية.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| المعلمات | النوع | الوصف |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds) | نوع حدود الصورة المصغرة للشكل. |
| scale_x | **float** | مقياس X |
| scale_y | **float** | مقياس Y |



### انظر أيضاً
* فئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* تعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* فئة [`ZoomFrame`](/slides/python-net/ar/aspose.slides/zoomframe)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)