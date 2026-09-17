---
title: get_image method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/sectionzoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Renvoie la vignette de forme.
            Le type de limites de vignette de forme ShapeThumbnailBounds.Shape est utilisé par défaut.

### Renvoie

Vignette de forme.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Renvoie la vignette de forme.

### Renvoie

Vignette de forme ou None dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu'une forme n'a pas d'éléments visibles.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds) | type des limites de vignette de forme. |
| scale_x | **float** | Échelle X |
| scale_y | **float** | Échelle Y |



### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* classe [`SectionZoomFrame`](/slides/python-net/fr/aspose.slides/sectionzoomframe)
* énumération [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)