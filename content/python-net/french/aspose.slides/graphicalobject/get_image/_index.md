---
title: get_image method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/graphicalobject/get_image/
weight: 30
---
## get_image(self) {#}
Renvoie la vignette de forme.  
Le type **ShapeThumbnailBounds.Shape** de limites de vignette de forme est utilisé par défaut.

### Retour

Vignette de forme.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Renvoie la vignette de forme.

### Retour

Vignette de forme ou None dans le cas où **ShapeThumbnailBounds.Appearance** est utilisé et qu'une forme n'a pas d'éléments visibles.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds) | Shape thumbnail bounds type. |
| scale_x | **float** | Échelle X |
| scale_y | **float** | Échelle Y |



### Voir aussi
* classe [`GraphicalObject`](/slides/python-net/fr/aspose.slides/graphicalobject)
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* énumération [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)