---
title: add_connector method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Crée une nouvelle forme de connecteur avec le style de modèle par défaut et l’ajoute à la fin de la collection de formes.

### Retour

Le [`IConnector`](/slides/python-net/fr/aspose.slides/iconnector) nouvellement créé.



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) | Le [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) du connecteur à ajouter. |
| x | **float** | La coordonnée x du cadre du connecteur, en points. |
| y | **float** | La coordonnée y du cadre du connecteur, en points. |
| width | **float** | La largeur du cadre du connecteur, en points. |
| height | **float** | La hauteur du cadre du connecteur, en points. |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Crée une nouvelle forme de connecteur et l’ajoute à la fin de la collection de formes, avec la possibilité d’appliquer le style de modèle par défaut.

### Retour

Le [`IConnector`](/slides/python-net/fr/aspose.slides/iconnector) nouvellement créé.



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) | Le [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) du connecteur à créer. |
| x | **float** | La coordonnée x du cadre du connecteur, en points. |
| y | **float** | La coordonnée y du cadre du connecteur, en points. |
| width | **float** | La largeur du cadre du connecteur, en points. |
| height | **float** | La hauteur du cadre du connecteur, en points. |
| create_from_template | **bool** | True pour appliquer le style de modèle par défaut (nom non vide, style simple) ; <br/><br/>false pour créer le connecteur avec les valeurs de propriétés par défaut. |



### Voir aussi
* classe [`IConnector`](/slides/python-net/fr/aspose.slides/iconnector)
* classe [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection)
* énumération [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)