---
title: get_image method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/zoomobject/get_image/
weight: 30
---
## get_image(self) {#}
بازگشت تصویر بندانگشتی شکل.
            نوع محدوده تصویر بندانگشتی ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض استفاده می‌شود.

### بازگشت

تصویر بندانگشتی شکل.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
بازگشت تصویر بندانگشتی شکل.

### بازگشت

تصویر بندانگشتی شکل یا None در صورتی که ShapeThumbnailBounds.Appearance استفاده شود و شکل عناصری قابل مشاهده نداشته باشد.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds) | نوع محدوده تصویر بندانگشتی شکل. |
| scale_x | **float** | مقیاس X |
| scale_y | **float** | مقیاس Y |



### موارد مرتبط
* کلاس [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds)
* کلاس [`ZoomObject`](/slides/python-net/fa/aspose.slides/zoomobject)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)