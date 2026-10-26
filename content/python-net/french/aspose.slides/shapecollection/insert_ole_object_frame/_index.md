---
title: insert_ole_object_frame method
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Crée un nouveau cadre d’objet OLE et l’insère dans la collection de formes à l’indice spécifié.

### Returns
Le [`IOleObjectFrame`](/slides/python-net/fr/aspose.slides/ioleobjectframe) créé.



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L’indice basé sur zéro à laquelle insérer le cadre d’objet OLE. |
| x | **float** | La coordonnée x du nouveau cadre OLE, en points. |
| y | **float** | La coordonnée y du nouveau cadre OLE, en points. |
| width | **float** | La largeur du nouveau cadre OLE, en points. |
| height | **float** | La hauteur du nouveau cadre OLE, en points. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/fr/aspose.slides/ioleembeddeddatainfo) | Les informations sur les données OLE incorporées ([`IOleEmbeddedDataInfo`](/slides/python-net/fr/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Crée un nouveau cadre d’objet OLE et l’insère dans la collection de formes à l’indice spécifié.

### Returns
Le cadre d’objet OLE créé.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| index | **int** | L’indice basé sur zéro à laquelle insérer le cadre d’objet OLE. |
| x | **float** | La coordonnée x du nouveau cadre OLE, en points. |
| y | **float** | La coordonnée y du nouveau cadre OLE, en points. |
| width | **float** | La largeur du nouveau cadre OLE, en points. |
| height | **float** | La hauteur du nouveau cadre OLE, en points. |
| class_name | **str** | Le nom de classe de l’objet OLE. |
| path | **str** | Le chemin vers le fichier lié.<br/><br/>Ce chemin est stocké tel quel dans la présentation.<br/><br/>            Si un chemin relatif est spécifié, le fichier sera inaccessible lors de l’ouverture<br/><br/>            de la présentation depuis un répertoire différent. |



### See Also
* classe [`IOleEmbeddedDataInfo`](/slides/python-net/fr/aspose.slides/ioleembeddeddatainfo)
* classe [`IOleObjectFrame`](/slides/python-net/fr/aspose.slides/ioleobjectframe)
* classe [`ShapeCollection`](/slides/python-net/fr/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)