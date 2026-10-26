---
title: get_image method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/autoshape/get_image/
weight: 60
---
## get_image(self) {#}
تصویر کوچک شکل را باز می‌گرداند.
ShapeThumbnailBounds.Shape نوع حاشیه تصویر کوچک شکل به‌صورت پیش‌فرض استفاده می‌شود.

### بازگشت

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
تصویر کوچک شکل را باز می‌گرداند.

### بازگشت

تصویر کوچک شکل یا None در صورتی که ShapeThumbnailBounds.Appearance استفاده شود و شکل عناصر قابل مشاهده‌ای نداشته باشد، باز می‌گردد.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| پارامتر | نوع | توضحیح |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds) | نوع حاشیه تصویر کوچک شکل. |
| scale_x | **float** | مقیاس X |
| scale_y | **float** | مقیاس Y |



### مراجع
* کلاس [`AutoShape`](/slides/python-net/fa/aspose.slides/autoshape)
* کلاس [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)