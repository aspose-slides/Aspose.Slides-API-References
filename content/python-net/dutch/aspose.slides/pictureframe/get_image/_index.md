---
title: get_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/pictureframe/get_image/
weight: 50
---
## get_image(self) {#}
Retourneert shape thumbnail.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

### Retour

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retourneert shape thumbnail.

### Retour

Shape thumbnail of None in het geval dat ShapeThumbnailBounds.Appearance wordt gebruikt en een shape geen zichtbare elementen heeft.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X-schaal |
| scale_y | **float** | Y-schaal |



### Zie ook
* klasse [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* klasse [`PictureFrame`](/slides/python-net/nl/aspose.slides/pictureframe)
* enumeratie [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)