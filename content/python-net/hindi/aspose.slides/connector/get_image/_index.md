---
title: get_image method
second_title: Aspose.Slides for Python via .NET API संदर्भ
description: 
type: docs
url: /hi/aspose.slides/connector/get_image/
weight: 50
---
## get_image(self) {#}
शेप थंबनेल लौटाता है।
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### वापसी

शेप थंबनेल।



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
शेप थंबनेल लौटाता है।

### वापसी

शेप थंबनेल या None यदि ShapeThumbnailBounds.Appearance प्रयोग किया गया हो और किसी shape में दृश्य तत्व न हों।



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/hi/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X पैमाना |
| scale_y | **float** | Y पैमाना |



### देखें
* class [`Connector`](/slides/python-net/hi/aspose.slides/connector)
* class [`IImage`](/slides/python-net/hi/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/hi/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/hi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)