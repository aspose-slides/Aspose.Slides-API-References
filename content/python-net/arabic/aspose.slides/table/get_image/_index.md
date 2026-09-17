---
title: get_image method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/table/get_image/
weight: 30
---
## get_image(self) {#}
تُرجع صورة مصغرة للشكل.
            نوع حدود صورة مصغرة للشكل ShapeThumbnailBounds.Shape يُستخدم بشكل افتراضي.

### Returns

الصورة المصغرة للشكل.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
تُرجع صورة مصغرة للشكل.

### Returns

الصورة المصغرة للشكل أو None في حال تم استخدام ShapeThumbnailBounds.Appearance ولا يحتوي الشكل على عناصر مرئية.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds) | نوع حدود صورة مصغرة للشكل. |
| scale_x | **float** | مقياس X |
| scale_y | **float** | مقياس Y |



### See Also
* الفئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* التعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* الفئة [`Table`](/slides/python-net/ar/aspose.slides/table)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)