---
title: get_image method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/legacydiagram/get_image/
weight: 50
---
## get_image(self) {#}
Renvoie shape thumbnail.
            ShapeThumbnailBounds.Shape le type des limites de la miniature de forme est utilisé par défaut.

### Valeur de retour

Shape thumbnail.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Renvoie shape thumbnail.

### Valeur de retour

Shape thumbnail ou None dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu'une forme n'a pas d'éléments visibles.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds) | Type des limites de la miniature de forme. |
| scale_x | **float** | Échelle X |
| scale_y | **float** | Échelle Y |



### Voir aussi
* class [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* class [`LegacyDiagram`](/slides/python-net/fr/aspose.slides/legacydiagram)
* enumeration [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)