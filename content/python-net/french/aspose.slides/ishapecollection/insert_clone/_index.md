---
title: insert_clone method
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/ishapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué.  
La forme clonée conserve la position et la taille de l’original.

### Retour

Le [`IShape`](/slides/python-net/fr/aspose.slides/ishape) nouvellement créé.



```python
def insert_clone(self, index, source_shape):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé sur zéro à lequel insérer la forme clonée. |
| source_shape | [`IShape`](/slides/python-net/fr/aspose.slides/ishape) | Le [`IShape`](/slides/python-net/fr/aspose.slides/ishape) à cloner. |


## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué.  
La nouvelle forme conserve la largeur et la hauteur de `source_shape`.

### Retour

Le [`IShape`](/slides/python-net/fr/aspose.slides/ishape) nouvellement créé.



```python
def insert_clone(self, index, source_shape, x, y):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé sur zéro à lequel insérer la forme clonée. |
| source_shape | [`IShape`](/slides/python-net/fr/aspose.slides/ishape) | Le [`IShape`](/slides/python-net/fr/aspose.slides/ishape) à cloner. |
| x | **float** | La coordonnée x du cadre de la forme clonée, en points. |
| y | **float** | La coordonnée y du cadre de la forme clonée, en points. |


## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
Crée une copie de la forme spécifiée et l’insère dans la collection de formes à l’index indiqué.

### Retour

Le [`IShape`](/slides/python-net/fr/aspose.slides/ishape) nouvellement créé.



```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé sur zéro à lequel insérer la forme clonée. |
| source_shape | [`IShape`](/slides/python-net/fr/aspose.slides/ishape) | Le [`IShape`](/slides/python-net/fr/aspose.slides/ishape) à cloner. |
| x | **float** | La coordonnée x du cadre de la forme clonée, en points. |
| y | **float** | La coordonnée y du cadre de la forme clonée, en points. |
| width | **float** | La largeur du cadre de la forme clonée, en points. |
| height | **float** | La hauteur du cadre de la forme clonée, en points. |



### Voir aussi
* classe [`IShape`](/slides/python-net/fr/aspose.slides/ishape)
* classe [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)