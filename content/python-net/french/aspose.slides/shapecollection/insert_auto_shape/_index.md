---
title: insert_auto_shape method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Crée une nouvelle forme automatique et l’insère dans la collection de formes à l’indice spécifié, en appliquant le formatage de modèle par défaut.

### Retour

Le nouvellement créé [`IAutoShape`](/slides/python-net/fr/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```



| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L’indice basé sur zéro à laquelle insérer la nouvelle forme automatique. |
| shape_type | [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) | Le [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) de la forme automatique à insérer. |
| x | **float** | La coordonnée x du cadre de la forme, en points. |
| y | **float** | La coordonnée y du cadre de la forme, en points. |
| width | **float** | La largeur du cadre de la forme, en points. |
| height | **float** | La hauteur du cadre de la forme, en points. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Crée une nouvelle forme automatique et l’insère dans la collection de formes à l’indice spécifié, éventuellement en l’initialisant avec le style de modèle par défaut.

### Retour

Le nouvellement créé [`IAutoShape`](/slides/python-net/fr/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L’indice basé sur zéro à laquelle insérer la forme automatique. |
| shape_type | [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) | Le [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) de la forme automatique à insérer. |
| x | **float** | La coordonnée x du cadre de la forme, en points. |
| y | **float** | La coordonnée y du cadre de la forme, en points. |
| width | **float** | La largeur du cadre de la forme, en points. |
| height | **float** | La hauteur du cadre de la forme, en points. |
| create_from_template | **bool** | True pour appliquer le style de modèle par défaut (incluant un nom non vide, un style simple et du texte centré) ; <br/><br/> false pour créer la forme avec toutes les propriétés définies à leurs valeurs par défaut. |



### Voir aussi
* classe [`IAutoShape`](/slides/python-net/fr/aspose.slides/iautoshape)
* classe [`ShapeCollection`](/slides/python-net/fr/aspose.slides/shapecollection)
* énumération [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)