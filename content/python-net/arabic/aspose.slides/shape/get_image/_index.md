---
title: get_image method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shape/get_image/
weight: 30
---
## get_image(self) {#}
يعيد صورة مصغرة للشكل.
            يتم استخدام نوع حدود صورة مصغرة للشكل ShapeThumbnailBounds.Shape بشكل افتراضي.

### Returns
صورة مصغرة للشكل.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
يعيد صورة مصغرة للشكل.

### Returns
صورة مصغرة للشكل أو None في حال تم استخدام ShapeThumbnailBounds.Appearance ولا يحتوي الشكل على عناصر مرئية.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds) | نوع حدود صورة مصغرة للشكل. |
| scale_x | **float** | مقياس X |
| scale_y | **float** | مقياس Y |



### See Also
* الفئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* الفئة [`Shape`](/slides/python-net/ar/aspose.slides/shape)
* تعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)