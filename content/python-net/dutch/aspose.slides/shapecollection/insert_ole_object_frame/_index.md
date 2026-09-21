---
title: insert_ole_object_frame method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Maakt een nieuw OLE-objectframe en voegt het in de vormverzameling in op de opgegeven index.

### Retourwaarde

Het nieuw aangemaakte [`IOleObjectFrame`](/slides/python-net/nl/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De index vanaf nul waarop het OLE-objectframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | **float** | De breedte van het nieuwe OLE-frame, in punten. |
| height | **float** | De hoogte van het nieuwe OLE-frame, in punten. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/nl/aspose.slides/ioleembeddeddatainfo) | De embedded OLE-data-informatie ([`IOleEmbeddedDataInfo`](/slides/python-net/nl/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Maakt een nieuw OLE-objectframe en voegt het in de vormverzameling in op de opgegeven index.

### Retourwaarde

Het nieuw aangemaakte OLE-objectframe.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De index vanaf nul waarop het OLE-objectframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | **float** | De breedte van het nieuwe OLE-frame, in punten. |
| height | **float** | De hoogte van het nieuwe OLE-frame, in punten. |
| class_name | **str** | De klassenaam van het OLE-object. |
| path | **str** | Het pad naar het gekoppelde bestand. <br/><br/>Dit pad wordt letterlijk opgeslagen in de presentatie.<br/><br/>Als een relatief pad wordt opgegeven, is het bestand niet toegankelijk bij het openen<br/><br/>van de presentatie vanuit een andere map. |



### Zie ook
* klasse [`IOleEmbeddedDataInfo`](/slides/python-net/nl/aspose.slides/ioleembeddeddatainfo)
* klasse [`IOleObjectFrame`](/slides/python-net/nl/aspose.slides/ioleobjectframe)
* klasse [`ShapeCollection`](/slides/python-net/nl/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)