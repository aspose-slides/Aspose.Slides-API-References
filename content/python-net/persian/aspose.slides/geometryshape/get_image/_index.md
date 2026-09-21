---
title: get_image method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/geometryshape/get_image/
weight: 50
---
## get_image(self) {#}
تصویر بندانگشتی شکل را برمی‌گرداند.
نوع bounds تصویر بندانگشتی شکل ShapeThumbnailBounds.Shape به‌طور پیش‌فرض استفاده می‌شود.

### بازگشت

تصویر بندانگشتی شکل.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
تصویر بندانگشتی شکل را برمی‌گرداند.

### بازگشت

تصویر بندانگشتی شکل یا None در صورتی که ShapeThumbnailBounds.Appearance استفاده شده باشد و شکل عناصر قابل رؤیتی نداشته باشد.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds) | نوع bounds تصویر بندانگشتی شکل. |
| scale_x | **float** | مقیاس X |
| scale_y | **float** | مقیاس Y |



### موارد مرتبط
* کلاس [`GeometryShape`](/slides/python-net/fa/aspose.slides/geometryshape)
* کلاس [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* شمارش [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)