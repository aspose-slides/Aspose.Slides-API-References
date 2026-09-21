---
title: get_image method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ishape/get_image/
weight: 30
---
## get_image(self) {#}
Returns shape thumbnail.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### بازگشت

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Returns shape thumbnail.

### بازگشت

Shape thumbnail or None in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds) | نوع محدوده تصویر کوچک شکل. |
| scale_x | **float** | مقیاس X |
| scale_y | **float** | مقیاس Y |



### مراجع
* کلاس [`IImage`](/slides/python-net/fa/aspose.slides/iimage)
* کلاس [`IShape`](/slides/python-net/fa/aspose.slides/ishape)
* شمارش [`ShapeThumbnailBounds`](/slides/python-net/fa/aspose.slides/shapethumbnailbounds)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)