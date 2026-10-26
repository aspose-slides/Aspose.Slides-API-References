---
title: get_image method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.smartart/smartartshape/get_image/
weight: 50
---
## get_image(self) {#}
تصویر بندانگشتی شکل را بازمی‌گرداند.  
نوع محدوده تصویر بندانگشتی ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض استفاده می‌شود.

### بازگشت

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
تصویر بندانگشتی شکل را بازمی‌گرداند.

### بازگشت

Shape thumbnail یا None در صورتی که ShapeThumbnailBounds.Appearance استفاده شود و شکلی عناصر قابل مشاهده نداشته باشد.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds) | نوع محدوده تصویر بندانگشتی شکل. |
| scale_x | **float** | مقیاس X |
| scale_y | **float** | مقیاس Y |



### موارد مرتبط
* class [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds)
* class [`SmartArtShape`](/slides/python-net/fa/aspose.slides.smartart/smartartshape)
* module [`aspose.slides.smartart`](/slides/python-net/fa/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)