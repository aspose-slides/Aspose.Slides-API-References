---
title: get_image method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/pictureframe/get_image/
weight: 50
---
## get_image(self) {#}
تصویر بند انگشتی شکل را برمی‌گرداند.
ShapeThumbnailBounds.Shape نوع محدوده تصویر بند انگشتی شکل به‌صورت پیش‌فرض استفاده می‌شود.

### Returns
تصویر بند انگشتی شکل.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
تصویر بند انگشتی شکل را برمی‌گرداند.

### Returns
تصویر بند انگشتی شکل یا None در صورتی که ShapeThumbnailBounds.Appearance استفاده شود و شکل عناصر قابل مشاهده‌ای نداشته باشد.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds) | نوع محدوده تصویر بند انگشتی شکل. |
| scale_x | **float** | مقیاس X |
| scale_y | **float** | مقیاس Y |

### موارد مرتبط
* کلاس [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* کلاس [`PictureFrame`](/slides/python-net/fa/aspose.slides/pictureframe)
* شمارش [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)