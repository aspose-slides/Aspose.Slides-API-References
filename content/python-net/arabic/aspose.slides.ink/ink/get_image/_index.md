---
title: get_image method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.ink/ink/get_image/
weight: 30
---
## get_image(self) {#}
يعيد الصورة المصغرة للشكل.
ShapeThumbnailBounds.Shape يُستخدم كنوع لحدود الصورة المصغرة للشكل افتراضيًا.

### القيمة المرجعة

الصورة المصغرة للشكل.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
يعيد الصورة المصغرة للشكل.

### القيمة المرجعة

الصورة المصغرة للشكل أو None في حالة استخدام ShapeThumbnailBounds.Appearance وعدم احتواء الشكل على عناصر مرئية.



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
* الفئة [`Ink`](/slides/python-net/ar/aspose.slides.ink/ink)
* التعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* الوحدة [`aspose.slides.ink`](/slides/python-net/ar/aspose.slides.ink)
* المكتبة [`Aspose.Slides`](/slides/python-net)