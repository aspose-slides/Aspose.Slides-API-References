---
title: get_image method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/videoframe/get_image/
weight: 50
---
## get_image(self) {#}
Renvoie la vignette de forme.
ShapeThumbnailBounds.Shape le type de limites de vignette de forme est utilisé par défaut.

### Valeur de retour

Vignette de forme.

```python
def get_image(self):
    ...
```

## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Renvoie la vignette de forme.

### Valeur de retour

Vignette de forme ou None dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu'une forme ne possède pas d'éléments visibles.

```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds) | Type de limites de vignette de forme. |
| scale_x | **float** | Échelle X |
| scale_y | **float** | Échelle Y |

### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* énumération [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds)
* classe [`VideoFrame`](/slides/python-net/fr/aspose.slides/videoframe)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)