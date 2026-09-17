---
title: get_image method
second_title: Aspose.Slides pour Python via .NET Référence API
description: 
type: docs
url: /fr/aspose.slides/zoomframe/get_image/
weight: 30
---
## get_image(self) {#}
Renvoie la vignette de la forme.
Le type de limites de vignette de forme ShapeThumbnailBounds.Shape est utilisé par défaut.

### Renvoie

Vignette de forme.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Renvoie la vignette de la forme.

### Renvoie

Vignette de forme ou None dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu'une forme n'a pas d'éléments visibles.



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
* classe [`ZoomFrame`](/slides/python-net/fr/aspose.slides/zoomframe)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)