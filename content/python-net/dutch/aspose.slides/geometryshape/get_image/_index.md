---
title: get_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/geometryshape/get_image/
weight: 50
---
## get_image(self) {#}
Retourneert shape miniatuur.  
ShapeThumbnailBounds.Shape vorm miniatuur grenzen type wordt standaard gebruikt.

### Returns

shape miniatuur.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retourneert shape miniatuur.

### Returns

shape miniatuur of None in het geval dat ShapeThumbnailBounds.Appearance wordt gebruikt en een vorm geen zichtbare elementen heeft.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X schaal |
| scale_y | **float** | Y schaal |



### Zie ook
* klasse [`GeometryShape`](/slides/python-net/nl/aspose.slides/geometryshape)
* klasse [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* enumeratie [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)