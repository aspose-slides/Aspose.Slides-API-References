---
title: add_ole_object_frame method
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Crée un nouveau cadre d’objet OLE et l’ajoute à la fin de la collection de formes.

### Valeur de retour

Le [`IOleObjectFrame`](/slides/python-net/fr/aspose.slides/ioleobjectframe) nouvellement créé.



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x | **float** | La coordonnée x du nouveau cadre OLE, en points. |
| y | **float** | La coordonnée y du nouveau cadre OLE, en points. |
| width | **float** | La largeur du nouveau cadre OLE, en points. |
| height | **float** | La hauteur du nouveau cadre OLE, en points. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/fr/aspose.slides/ioleembeddeddatainfo) | Les informations des données OLE intégrées ([`IOleEmbeddedDataInfo`](/slides/python-net/fr/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Crée un nouveau cadre d’objet OLE et l’ajoute à la fin de la collection de formes.

### Valeur de retour

Le [`IOleObjectFrame`](/slides/python-net/fr/aspose.slides/ioleobjectframe) nouvellement créé.



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| x | **float** | La coordonnée x du nouveau cadre OLE, en points. |
| y | **float** | La coordonnée y du nouveau cadre OLE, en points. |
| width | **float** | La largeur du nouveau cadre OLE, en points. |
| height | **float** | La hauteur du nouveau cadre OLE, en points. |
| class_name | **str** | Le nom de classe de l’objet OLE. |
| path | **str** | Le chemin vers le fichier lié. <br/><br/>Ce chemin est stocké tel quel dans la présentation.<br/><br/>            Si un chemin relatif est spécifié, le fichier sera inaccessible lors de l'ouverture<br/><br/>            de la présentation depuis un répertoire différent. |



### Voir aussi
* classe [`IOleEmbeddedDataInfo`](/slides/python-net/fr/aspose.slides/ioleembeddeddatainfo)
* classe [`IOleObjectFrame`](/slides/python-net/fr/aspose.slides/ioleobjectframe)
* classe [`IShapeCollection`](/slides/python-net/fr/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)