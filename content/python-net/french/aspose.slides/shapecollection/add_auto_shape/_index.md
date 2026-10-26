---
title: add_auto_shape method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Crée une nouvelle forme auto avec un formatage par défaut et l'ajoute à la fin de la collection de formes.

### Retour

Le [`IAutoShape`](/slides/python-net/fr/aspose.slides/iautoshape) nouvellement créé.



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) | Le [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) de la forme auto à ajouter. |
| x | **float** | La coordonnée x du cadre de la forme, en points. |
| y | **float** | La coordonnée y du cadre de la forme, en points. |
| width | **float** | La largeur du cadre de la forme, en points. |
| height | **float** | La hauteur du cadre de la forme, en points. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Crée une nouvelle forme auto et l'ajoute à la fin de la collection de formes, en l'initialisant éventuellement avec le formatage de modèle par défaut.

### Retour

Le [`IAutoShape`](/slides/python-net/fr/aspose.slides/iautoshape) nouvellement créé.



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) | Le [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) de la forme auto à ajouter. |
| x | **float** | La coordonnée x du cadre de la forme, en points. |
| y | **float** | La coordonnée y du cadre de la forme, en points. |
| width | **float** | La largeur du cadre de la forme, en points. |
| height | **float** | La hauteur du cadre de la forme, en points. |
| create_from_template | **bool** | True pour appliquer le style de modèle par défaut (style simple, texte centré et nom non vide)<br/><br/>            à la nouvelle forme ; false pour créer la forme avec toutes les propriétés définies à leurs valeurs par défaut. |



### Voir aussi
* classe [`IAutoShape`](/slides/python-net/fr/aspose.slides/iautoshape)
* classe [`ShapeCollection`](/slides/python-net/fr/aspose.slides/shapecollection)
* énumération [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)