---
title: get_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.ink/inkactions/get_image/
weight: 30
---
## get_image(self) {#}
Retourneert shape thumbnail.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type wordt standaard gebruikt.

### Retour

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retourneert shape thumbnail.

### Retour

Shape thumbnail of None wanneer ShapeThumbnailBounds.Appearance wordt gebruikt en een shape geen zichtbare elementen heeft.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X-schaal |
| scale_y | **float** | Y-schaal |



### Zie ook
* klasse [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* klasse [`InkActions`](/slides/python-net/nl/aspose.slides.ink/inkactions)
* enumeratie [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides.ink`](/slides/python-net/nl/aspose.slides.ink)
* bibliotheek [`Aspose.Slides`](/slides/python-net)