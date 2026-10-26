---
title: get_image method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/connector/get_image/
weight: 50
---
## get_image(self) {#}
Retourneert shape miniatuur.
            ShapeThumbnailBounds.Shape shape thumbnail bounds type wordt standaard gebruikt.

### Retourneert

Shape miniatuur.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Retourneert shape miniatuur.

### Retourneert

Shape miniatuur of None in het geval dat ShapeThumbnailBounds.Appearance wordt gebruikt en een shape geen zichtbare elementen heeft.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds) | Shape thumbnail grens type. |
| scale_x | **float** | X-schaal |
| scale_y | **float** | Y-schaal |

### Zie ook
* klasse [`Connector`](/slides/python-net/nl/aspose.slides/connector)
* klasse [`IImage`](/slides/python-net/nl/aspose.slides/iimage)
* enumeratie [`ShapeThumbnailBounds`](/slides/python-net/nl/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)