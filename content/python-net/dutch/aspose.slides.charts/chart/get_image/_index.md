---
title: get_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.charts/chart/get_image/
weight: 40
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

Shape thumbnail of None in het geval dat ShapeThumbnailBounds.Appearance wordt gebruikt en een shape geen zichtbare elementen heeft.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | X scale |
| scale_y | **float** | Y scale |



### Zie ook
* klasse [`Chart`](/slides/python-net/nl/aspose.slides.charts/chart)
* klasse [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides.charts`](/slides/python-net/nl/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)