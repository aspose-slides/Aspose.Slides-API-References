---
title: get_image method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/connector/get_image/
weight: 50
---
## get_image(self) {#}
تصویر کوچک شکل را برمی‌گرداند.
            ShapeThumbnailBounds.Shape نوع مرز تصویر کوچک شکل به طور پیش‌فرض استفاده می‌شود.

### بازگرداندن

تصویر کوچک شکل.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
تصویر کوچک شکل را برمی‌گرداند.

### بازگرداندن

تصویر کوچک شکل یا None در صورتی که ShapeThumbnailBounds.Appearance استفاده شود و یک شکل عناصر قابل مشاهده نداشته باشد.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds) | نوع مرز تصویر کوچک شکل. |
| scale_x | **float** | مقیاس X |
| scale_y | **float** | مقیاس Y |

### موارد مرتبط
* کلاس [`Connector`](/slides/python-net/fa/aspose.slides/connector)
* کلاس [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)