---
title: get_image method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iparagraph/get_image/
weight: 10
---


## get_image {#}
Returns an image of the paragraph.

### Returns

An image containing the rendered paragraph, or **None**
             if the paragraph cannot be found in its parent collection, has no valid
             rendering bounds, or an error occurs while rendering the image.



```python
def get_image(self):
    ...
```



## get_image {#float-float}
Returns an image of the paragraph with the specified scale.

### Returns

An image containing the rendered paragraph, or **None**
             if the paragraph cannot be found in its parent collection, has no valid
             rendering bounds, or an error occurs while rendering the image.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| scale_x | **float** | The horizontal scale factor applied to the paragraph image. |
| scale_y | **float** | The vertical scale factor applied to the paragraph image. |



### See Also
* class [`IImage`](/slides/python-net/aspose.slides/iimage)
* class [`IParagraph`](/slides/python-net/aspose.slides/iparagraph)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

