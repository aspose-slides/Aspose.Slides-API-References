---
title: get_image method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/autoshape/get_image/
weight: 60
---
## get_image(self) {#}
Renvoie la miniature de Shape.  
ShapeThumbnailBounds.Shape shape thumbnail bounds type est utilisé par défaut.

### Renvoie

Shape miniature.



```python
def get_image(self):
    ...
```



## get_image(self, bounds, scale_x, scale_y) {#shapethumbnailbounds-float-float}
Renvoie la miniature de Shape.

### Renvoie

Shape miniature ou None dans le cas où ShapeThumbnailBounds.Appearance est utilisé et qu'une shape n'a pas d'éléments visibles.



```python
def get_image(self, bounds, scale_x, scale_y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| bounds | [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds) | type des limites de la miniature de Shape. |
| scale_x | **float** | Échelle X |
| scale_y | **float** | Échelle Y |



### Voir aussi
* classe [`AutoShape`](/slides/python-net/fr/aspose.slides/autoshape)
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* énumération [`ShapeThumbnailBounds`](/slides/python-net/fr/aspose.slides/shapethumbnailbounds)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)