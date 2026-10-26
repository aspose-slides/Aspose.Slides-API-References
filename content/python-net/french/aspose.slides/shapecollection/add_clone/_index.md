---
title: add_clone method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/shapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes.  
La forme clonée conserve la position et la taille de l'original.

### Retour

Le [`IShape`](/slides/python-net/fr/aspose.slides/ishape) nouvellement créé.



```python
def add_clone(self, source_shape):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/fr/aspose.slides/ishape) | Le [`IShape`](/slides/python-net/fr/aspose.slides/ishape) à cloner. |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes.  
La nouvelle forme conserve la largeur et la hauteur de la `source_shape`.

### Retour

Le [`IShape`](/slides/python-net/fr/aspose.slides/ishape) nouvellement créé.



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/fr/aspose.slides/ishape) | La forme à cloner. |
| x | **float** | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | **float** | La coordonnée y du cadre de la nouvelle forme, en points. |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Crée une copie de la forme spécifiée et l'ajoute à la fin de la collection de formes.

### Retour

Le [`IShape`](/slides/python-net/fr/aspose.slides/ishape) nouvellement créé.



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/fr/aspose.slides/ishape) | La forme à cloner. |
| x | **float** | La coordonnée x du cadre de la nouvelle forme, en points. |
| y | **float** | La coordonnée y du cadre de la nouvelle forme, en points. |
| width | **float** | La largeur du cadre de la nouvelle forme, en points. |
| height | **float** | La hauteur du cadre de la nouvelle forme, en points. |



### Voir aussi
* classe [`IShape`](/slides/python-net/fr/aspose.slides/ishape)
* classe [`ShapeCollection`](/slides/python-net/fr/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)