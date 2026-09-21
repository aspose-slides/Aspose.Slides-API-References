---
title: get_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.smartart/smartartshape/get_image/
weight: 50
---
## get_image(self) {#}
Retourneert een miniatuur van de vorm.
            ShapeThumbnailBounds.Shape vorm miniatuur grenzen type wordt standaard gebruikt.

### Retour

Miniatuur van de vorm.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retourneert een miniatuur van de vorm.

### Retour

Miniatuur van de vorm of None in het geval dat ShapeThumbnailBounds.Appearance wordt gebruikt en een vorm geen zichtbare elementen heeft.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds) | Type van de vorm miniatuurgrenzen. |
| scale_x | **float** | X schaal |
| scale_y | **float** | Y schaal |



### Zie ook
* klasse [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* enumeratie [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds)
* klasse [`SmartArtShape`](/slides/python-net/nl/aspose.slides.smartart/smartartshape)
* module [`aspose.slides.smartart`](/slides/python-net/nl/aspose.slides.smartart)
* bibliotheek [`Aspose.Slides`](/slides/python-net)