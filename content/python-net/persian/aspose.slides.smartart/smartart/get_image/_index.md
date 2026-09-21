---
title: get_image method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.smartart/smartart/get_image/
weight: 30
---
## get_image(self) {#}
یک تصویر بندانگشتی از شکل را برمی‌گرداند.
            ShapeThumbnailBounds.Shape نوع محدوده تصویر بندانگشتی به‌طور پیش‌فرض استفاده می‌شود.

### بازگشت

تصویر بندانگشتی شکل.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
یک تصویر بندانگشتی از شکل را برمی‌گرداند.

### بازگشت

تصویر بندانگشتی شکل یا None در صورتی که ShapeThumbnailBounds.Appearance استفاده شود و شکلی عناصر قابل مشاهده نداشته باشد.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds) | نوع محدوده تصویر بندانگشتی شکل. |
| scale_x | **float** | مقیاس X |
| scale_y | **float** | مقیاس Y |



### موارد مرتبط
* کلاس [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* شمارش [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds)
* کلاس [`SmartArt`](/slides/python-net/fa/aspose.slides.smartart/smartart)
* ماژول [`aspose.slides.smartart`](/slides/python-net/fa/aspose.slides.smartart)
* کتابخانه [`Aspose.Slides`](/slides/python-net)