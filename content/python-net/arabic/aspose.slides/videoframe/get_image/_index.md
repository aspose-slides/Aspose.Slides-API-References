---
title: get_image method
second_title: Aspose.Slides للبايثون عبر .NET – مرجع API
description: 
type: docs
url: /ar/aspose.slides/videoframe/get_image/
weight: 50
---
## get_image(self) {#}
يقوم بإرجاع صورة مصغرة للشكل.
            يتم استخدام نوع حدود صورة مصغرة للشكل ShapeThumbnailBounds.Shape بشكل افتراضي.

### القيمة المرجعة

صورة مصغرة للشكل.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
يقوم بإرجاع صورة مصغرة للشكل.

### القيمة المرجعة

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
* الفئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* التعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* الفئة [`VideoFrame`](/slides/python-net/ar/aspose.slides/videoframe)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)