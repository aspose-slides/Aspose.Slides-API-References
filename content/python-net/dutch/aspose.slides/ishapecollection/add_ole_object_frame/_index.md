---
title: add_ole_object_frame method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Maakt een nieuw OLE object frame en voegt het toe aan het einde van de shape-collectie.

### Retour

Het nieuw gemaakte [`IOleObjectFrame`](/slides/python-net/nl/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | **float** | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | **float** | De breedte van het nieuwe OLE-frame, in punten. |
| height | **float** | De hoogte van het nieuwe OLE-frame, in punten. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/nl/aspose.slides/ioleembeddeddatainfo) | De informatie over de ingebedde OLE-gegevens ([`IOleEmbeddedDataInfo`](/slides/python-net/nl/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Maakt een nieuw OLE object frame en voegt het toe aan het einde van de shape-collectie.

### Retour

Het nieuw gemaakte [`IOleObjectFrame`](/slides/python-net/nl/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | **float** | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | **float** | De breedte van het nieuwe OLE-frame, in punten. |
| height | **float** | De hoogte van het nieuwe OLE-frame, in punten. |
| class_name | **str** | De klassenaam van het OLE-object. |
| path | **str** | Het pad naar het gekoppelde bestand. <br/><br/>Dit pad wordt letterlijk opgeslagen in de presentatie.<br/><br/>            Als een relatief pad wordt opgegeven, zal het bestand ontoegankelijk zijn bij het openen<br/><br/>            van de presentatie vanuit een andere map. |



### Zie ook
* klasse [`IOleEmbeddedDataInfo`](/slides/python-net/nl/aspose.slides/ioleembeddeddatainfo)
* klasse [`IOleObjectFrame`](/slides/python-net/nl/aspose.slides/ioleobjectframe)
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)