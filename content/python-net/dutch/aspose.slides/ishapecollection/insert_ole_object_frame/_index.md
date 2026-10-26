---
title: insert_ole_object_frame method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Maakt een nieuw OLE-objectframe en voegt het toe aan de vormcollectie op de opgegeven index.

### Retourneert

Het nieuw aangemaakte [`IOleObjectFrame`](/slides/python-net/nl/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nul-gebaseerde index waarop het OLE-objectframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | **float** | De breedte van het nieuwe OLE-frame, in punten. |
| height | **float** | De hoogte van het nieuwe OLE-frame, in punten. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/nl/aspose.slides/ioleembeddeddatainfo) | De ingesloten OLE-gegevensinformatie ([`IOleEmbeddedDataInfo`](/slides/python-net/nl/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Maakt een nieuw OLE-objectframe en voegt het toe aan de vormcollectie op de opgegeven index.

### Retourneert

Het nieuw aangemaakte [`IOleObjectFrame`](/slides/python-net/nl/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | **int** | De nul-gebaseerde index waarop het OLE-objectframe moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het nieuwe OLE-frame, in punten. |
| y | **float** | De y-coördinaat van het nieuwe OLE-frame, in punten. |
| width | **float** | De breedte van het nieuwe OLE-frame, in punten. |
| height | **float** | De hoogte van het nieuwe OLE-frame, in punten. |
| class_name | **str** | De klassenaam van het OLE-object. |
| path | **str** | Het pad naar het gekoppelde bestand. <br/><br/>Dit pad wordt letterlijk opgeslagen in de presentatie.<br/><br/>If a relative path is specified, the file will be inaccessible when opening<br/><br/>the presentation from a different directory. |



### Zie ook
* klasse [`IOleEmbeddedDataInfo`](/slides/python-net/nl/aspose.slides/ioleembeddeddatainfo)
* klasse [`IOleObjectFrame`](/slides/python-net/nl/aspose.slides/ioleobjectframe)
* klasse [`IShapeCollection`](/slides/python-net/nl/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)