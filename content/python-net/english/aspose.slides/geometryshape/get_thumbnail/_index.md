---
title: get_thumbnail method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/geometryshape/get_thumbnail/
weight: 60
---


## get_thumbnail {#}
Returns shape thumbnail.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Returns

Shape thumbnail.



```python
def get_thumbnail(self):
    ...
```



## get_thumbnail {#shapethumbnailbounds-float-float}
Returns shape thumbnail.

### Returns

Shape thumbnail or None in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.



```python
def get_thumbnail(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X scale |
| scale_y | **float** | Y scale |



### See Also
* class [`GeometryShape`](/slides/python-net/aspose.slides/geometryshape)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

