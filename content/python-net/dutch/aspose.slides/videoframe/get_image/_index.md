---
title: get_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/videoframe/get_image/
weight: 50
---
## get_image(self) {#}
Retourneert een shape thumbnail.  
ShapeThumbnailBounds.Shape type van shape thumbnail bounds wordt standaard gebruikt.

### Returns

Shape-miniatuur.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retourneert een shape thumbnail.

### Returns

Shape-miniatuur of None in het geval dat ShapeThumbnailBounds.Appearance wordt gebruikt en een shape geen zichtbare elementen heeft.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds) | type van shape thumbnail bounds. |
| scale_x | **float** | X-schaal |
| scale_y | **float** | Y-schaal |



### Zie ook
* klasse [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* enumeratie [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds)
* klasse [`VideoFrame`](/slides/python-net/nl/aspose.slides/videoframe)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)