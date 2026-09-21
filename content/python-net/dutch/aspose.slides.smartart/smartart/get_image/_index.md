---
title: get_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.smartart/smartart/get_image/
weight: 30
---
## get_image(self) {#}
Retourneert shape thumbnail.  
ShapeThumbnailBounds.Shape shape thumbnail bounds type wordt standaard gebruikt.

### Returns

Shape thumbnail



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retourneert shape thumbnail.

### Returns

Shape thumbnail of None in het geval dat ShapeThumbnailBounds.Appearance wordt gebruikt en een shape geen zichtbare elementen heeft.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X schaal |
| scale_y | **float** | Y schaal |



### See Also
* class [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds)
* class [`SmartArt`](/slides/python-net/nl/aspose.slides.smartart/smartart)
* module [`aspose.slides.smartart`](/slides/python-net/nl/aspose.slides.smartart)
* library [`Aspose.Slides`](/slides/python-net)