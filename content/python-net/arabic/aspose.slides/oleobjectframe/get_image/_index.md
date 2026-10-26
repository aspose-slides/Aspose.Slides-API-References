---
title: get_image method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/oleobjectframe/get_image/
weight: 30
---
## get_image(self) {#}
يُعيد الصورة المصغرة للشكل.
            يُستخدم النوع ShapeThumbnailBounds.Shape كنوع حدود الصورة المصغرة للشكل بشكل افتراضي.

### القيمة المرجعة

الصورة المصغرة للشكل.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
يُعيد الصورة المصغرة للشكل.

### القيمة المرجعة

الصورة المصغرة للشكل أو None في حالة استخدام ShapeThumbnailBounds.Appearance وعدم وجود عناصر مرئية للشكل.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| معامل | نوع | الوصف |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds) | نوع حدود الصورة المصغرة للشكل. |
| scale_x | **float** | مقياس X |
| scale_y | **float** | مقياس Y |



### انظر أيضًا
* فئة [`IImage`](/slides/python-net/ar/aspose.slides/iimage)
* فئة [`OleObjectFrame`](/slides/python-net/ar/aspose.slides/oleobjectframe)
* تعداد [`ShapeThumbnailBounds`](/slides/python-net/ar/aspose.slides/shapethumbnailbounds)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)