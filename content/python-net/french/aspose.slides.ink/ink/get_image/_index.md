---
title: get_image method
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides.ink/ink/get_image/
weight: 30
---
## get_image(self) {#}
Renvoie la vignette shape.
ShapeThumbnailBounds.Shape shape thumbnail bounds type est utilisé par défaut.

### Retour

miniature Shape.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Renvoie la vignette shape.

### Retour

vignette Shape ou None dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu'une shape n'a pas d'éléments visibles.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds) | type de limites de vignette Shape. |
| scale_x | **float** | échelle X |
| scale_y | **float** | échelle Y |

### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* classe [`Ink`](/slides/python-net/fr/aspose.slides.ink/ink)
* énumération [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides.ink`](/slides/python-net/fr/aspose.slides.ink)
* bibliothèque [`Aspose.Slides`](/slides/python-net)