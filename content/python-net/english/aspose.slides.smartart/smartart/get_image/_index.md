﻿---
title: get_image method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.smartart/smartart/get_image/
weight: 30
---


## get_image {#}
Returns shape thumbnail.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Returns

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image {#shapethumbnailbounds-float-float}
Returns shape thumbnail.

### Returns

Shape thumbnail or None in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X scale |
| scale_y | **float** | Y scale |



### See Also
* class [`IImage`](/slides/python-net/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/aspose.slides/shapethumbnailbounds)
* class [`SmartArt`](/slides/python-net/aspose.slides.smartart/smartart)
* module [`aspose.slides.smartart`](/slides/python-net/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)

