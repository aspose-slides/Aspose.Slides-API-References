---
title: get_image method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/groupshape/get_image/
weight: 30
---
## get_image(self) {#}
تصویر بندانگشتی شکل را برمی‌گرداند.
            ShapeThumbnailBounds.Shape نوع محدوده تصویر بندانگشتی شکل به طور پیش‌فرض استفاده می‌شود.

### بازگشت

تصویر بندانگشتی شکل.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
تصویر بندانگشتی شکل را برمی‌گرداند.

### بازگشت

تصویر بندانگشتی شکل یا None در صورتی که ShapeThumbnailBounds.Appearance استفاده شود و شکل عناصری قابل مشاهده نداشته باشد.

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
* کلاس [`GroupShape`](/slides/python-net/fa/aspose.slides/groupshape)
* کلاس [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* شمارش [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)