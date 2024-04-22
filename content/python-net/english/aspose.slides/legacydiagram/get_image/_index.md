---
title: get_image method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/legacydiagram/get_image/
weight: 50
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

Shape thumbnail or null in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.



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
* class [`LegacyDiagram`](/slides/python-net/aspose.slides/legacydiagram)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

