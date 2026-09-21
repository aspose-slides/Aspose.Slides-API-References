---
title: get_image method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.ink/ink/get_image/
weight: 30
---
## get_image(self) {#}
تصویر بندانگشتی شکل را برمی‌گرداند.
            نوع محدودهٔ بندانگشتی شکل ShapeThumbnailBounds.Shape به طور پیش‌فرض استفاده می‌شود.

### بازگشت

تصویر بندانگشتی شکل.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
تصویر بندانگشتی شکل را برمی‌گرداند.

### بازگشت

در صورتی که ShapeThumbnailBounds.Appearance استفاده شده باشد و شکلی عناصر قابل مشاهده نداشته باشد، تصویر بندانگشتی شکل یا None برگردانده می‌شود.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds) | نوع محدودهٔ تصویر بندانگشتی شکل. |
| scale_x | **float** | مقیاس X |
| scale_y | **float** | مقیاس Y |

### موارد مرتبط
* کلاس [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* کلاس [`Ink`](/slides/python-net/fa/aspose.slides.ink/ink)
* شمارش [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds)
* ماژول [`aspose.slides.ink`](/slides/python-net/fa/aspose.slides.ink)
* کتابخانه [`Aspose.Slides`](/slides/python-net)