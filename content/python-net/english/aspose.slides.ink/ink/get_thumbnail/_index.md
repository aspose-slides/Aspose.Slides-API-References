---
title: get_thumbnail method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.ink/ink/get_thumbnail/
weight: 30
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

Shape thumbnail or null in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.



```python
def get_thumbnail(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | ShapeThumbnailBounds | Shape thumbnail bounds type. |
| scale_x | float | X scale |
| scale_y | float | Y scale |



### See Also
* class [`Ink`](/slides/python-net/aspose.slides.ink/ink)
* module [`aspose.slides.ink`](/slides/python-net/aspose.slides.ink)
* library [`Aspose.Slides`](/slides/python-net)
