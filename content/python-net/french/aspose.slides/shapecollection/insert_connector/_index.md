---
title: insert_connector method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Crée une nouvelle forme de connecteur et l’insère dans la collection de formes à l’index spécifié,
            en appliquant le style de modèle par défaut.

### Renvoie

Le [`IConnector`](/slides/python-net/fr/aspose.slides/iconnector) nouvellement créé.



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé sur zéro où insérer la forme de connecteur. |
| shape_type | [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) | Le [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) de la forme de connecteur à insérer. |
| x | **float** | La coordonnée x du cadre du connecteur, en points. |
| y | **float** | La coordonnée y du cadre du connecteur, en points. |
| width | **float** | La largeur du cadre du connecteur, en points. |
| height | **float** | La hauteur du cadre du connecteur, en points. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Crée une nouvelle forme de connecteur et l’insère dans la collection de formes à l’index spécifié,
            en appliquant éventuellement le style de modèle par défaut.

### Renvoie

Le [`IConnector`](/slides/python-net/fr/aspose.slides/iconnector) nouvellement créé.



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L'index basé sur zéro où insérer la forme de connecteur. |
| shape_type | [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) | Le [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype) de la forme de connecteur à insérer. |
| x | **float** | La coordonnée x du cadre du connecteur, en points. |
| y | **float** | La coordonnée y du cadre du connecteur, en points. |
| width | **float** | La largeur du cadre du connecteur, en points. |
| height | **float** | La hauteur du cadre du connecteur, en points. |
| create_from_template | **bool** | True pour appliquer le style de modèle par défaut (nom non vide, style simple);<br/><br/>            false pour créer le connecteur avec les valeurs de propriété par défaut. |



### Voir aussi
* classe [`IConnector`](/slides/python-net/fr/aspose.slides/iconnector)
* classe [`ShapeCollection`](/slides/python-net/fr/aspose.slides/shapecollection)
* énumération [`ShapeType`](/slides/python-net/fr/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)