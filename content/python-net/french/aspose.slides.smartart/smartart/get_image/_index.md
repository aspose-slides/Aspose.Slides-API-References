---
title: get_image method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides.smartart/smartart/get_image/
weight: 30
---
## get_image(self) {#}
Renvoie la miniature de la forme.
ShapeThumbnailBounds.Shape type de limites de la miniature de forme est utilisé par défaut.

### Retour

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Renvoie la miniature de la forme.

### Retour

Shape thumbnail ou None dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu'une forme n'a pas d'éléments visibles.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds) | Type de limites de la miniature de forme. |
| scale_x | **float** | Échelle X |
| scale_y | **float** | Échelle Y |



### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* énumération [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds)
* classe [`SmartArt`](/slides/python-net/fr/aspose.slides.smartart/smartart)
* module [`aspose.slides.smartart`](/slides/python-net/fr/aspose.slides.smartart)
* bibliothèque [`Aspose.Slides`](/slides/python-net)