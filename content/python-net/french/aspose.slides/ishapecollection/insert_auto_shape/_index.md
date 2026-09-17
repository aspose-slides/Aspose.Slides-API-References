---
title: insert_auto_shape method
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Crée une nouvelle forme automatique et l'insère dans la collection de formes à l'index spécifié, en appliquant le formatage de modèle par défaut.

### Retour

Le [`IAutoShape`](/slides/python-net/fr/aspose.slides/iautoshape) nouvellement créé.



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé sur zéro où insérer la nouvelle forme automatique. |
| shape_type | [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) | Le [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) de la forme automatique à insérer. |
| x | **float** | La coordonnée x du cadre de la forme, en points. |
| y | **float** | La coordonnée y du cadre de la forme, en points. |
| width | **float** | La largeur du cadre de la forme, en points. |
| height | **float** | La hauteur du cadre de la forme, en points. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Crée une nouvelle forme automatique et l'insère dans la collection de formes à l'index spécifié, en l'initialisant éventuellement avec le style de modèle par défaut.

### Retour

Le [`IAutoShape`](/slides/python-net/fr/aspose.slides/iautoshape) nouvellement créé.



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé sur zéro où insérer la forme automatique. |
| shape_type | [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) | Le [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) de la forme automatique à insérer. |
| x | **float** | La coordonnée x du cadre de la forme, en points. |
| y | **float** | La coordonnée y du cadre de la forme, en points. |
| width | **float** | La largeur du cadre de la forme, en points. |
| height | **float** | La hauteur du cadre de la forme, en points. |
| create_from_template | **bool**| Vrai pour appliquer le style de modèle par défaut (incluant un nom non vide, un style simple et un texte centré) ; <br/><br/>            faux pour créer la forme avec toutes les propriétés définies à leurs valeurs par défaut. |



### Voir aussi
* classe [`IAutoShape`](/slides/python-net/fr/aspose.slides/iautoshape)
* classe [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection)
* énumération [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)