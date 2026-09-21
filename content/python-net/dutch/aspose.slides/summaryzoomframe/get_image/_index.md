---
title: get_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/summaryzoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Retourneert een Shape miniatuur.
            ShapeThumbnailBounds.Shape shape miniatuur begrenzingstype wordt standaard gebruikt.

### Retour

Shape miniatuur.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retourneert een Shape miniatuur.

### Retour

Shape miniatuur of None in het geval dat ShapeThumbnailBounds.Appearance wordt gebruikt en een shape geen zichtbare elementen heeft.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds) | Shape miniatuur begrenzingstype. |
| scale_x | **float** | X-schaal |
| scale_y | **float** | Y-schaal |



### Zie ook
* class [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds)
* class [`SummaryZoomFrame`](/slides/python-net/nl/aspose.slides/summaryzoomframe)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)