---
title: get_image method
second_title: مرجع API Aspose.Slides لـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/connector/get_image/
weight: 50
---
## get_image(self) {#}
يعيد صورة مصغرة للشكل.
            يُستخدم نوع حدود الصورة المصغرة للشكل افتراضيًا.

### الإرجاع

الصورة المصغرة للشكل.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
يعيد صورة مصغرة للشكل.

### الإرجاع

الصورة المصغرة للشكل أو None في الحالة التي يتم فيها استخدام ShapeThumbnailBounds.Appearance ولا يحتوي الشكل على عناصر مرئية.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| الوسيط | النوع | الوصف |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds) | نوع حدود الصورة المصغرة للشكل. |
| scale_x | **float** | مقياس X |
| scale_y | **float** | مقياس Y |



### انظر أيضًا
* الفئة [`Connector`](/slides/python-net/ar/aspose.slides/connector)
* الفئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* التعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)