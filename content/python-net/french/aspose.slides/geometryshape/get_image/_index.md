---
title: get_image method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/geometryshape/get_image/
weight: 50
---
## get_image(self) {#}
Renvoie la vignette de forme.
            ShapeThumbnailBounds.Shape type de limites de vignette de forme est utilisé par défaut.

### Valeur de retour

vignette de forme.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Renvoie la vignette de forme.

### Valeur de retour

vignette de forme ou None dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu'une forme n'a pas d'éléments visibles.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds) | type de limites de vignette de forme. |
| scale_x | **float** | échelle X |
| scale_y | **float** | échelle Y |



### Voir aussi
* classe [`GeometryShape`](/slides/python-net/fr/aspose.slides/geometryshape)
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* énumération [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)