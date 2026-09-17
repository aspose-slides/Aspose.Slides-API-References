---
title: insert_ole_object_frame method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Erstellt einen neuen OLE-Objektrahmen und fügt ihn an der angegebenen Position in die Formensammlung ein.

### Rückgabewert

Der neu erstellte [`IOleObjectFrame`](/slides/python-net/de/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem der OLE-Objektrahmen eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen OLE-Rahmens, in Punkten. |
| y | **float** | Die y-Koordinate des neuen OLE-Rahmens, in Punkten. |
| width | **float** | Die Breite des neuen OLE-Rahmens, in Punkten. |
| height | **float** | Die Höhe des neuen OLE-Rahmens, in Punkten. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/de/aspose.slides/ioleembeddeddatainfo) | Die eingebetteten OLE-Dateninformationen ([`IOleEmbeddedDataInfo`](/slides/python-net/de/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Erstellt einen neuen OLE-Objektrahmen und fügt ihn an der angegebenen Position in die Formensammlung ein.

### Rückgabewert

Der neu erstellte OLE-Objektrahmen.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Der nullbasierte Index, an dem der OLE-Objektrahmen eingefügt werden soll. |
| x | **float** | Die x-Koordinate des neuen OLE-Rahmens, in Punkten. |
| y | **float** | Die y-Koordinate des neuen OLE-rahmens, in Punkten. |
| width | **float** | Die Breite des neuen OLE-rahmens, in Punkten. |
| height | **float** | Die Höhe des neuen OLE-rahmens, in Punkten. |
| class_name | **str** | Der Klassenname des OLE-Objekts. |
| path | **str** | Der Pfad zur verknüpften Datei. <br/><br/>Dieser Pfad wird unverändert in der Präsentation gespeichert.<br/><br/>            Wenn ein relativer Pfad angegeben wird, ist die Datei beim Öffnen<br/><br/>            der Präsentation aus einem anderen Verzeichnis nicht zugänglich. |



### Siehe auch
* Klasse [`IOleEmbeddedDataInfo`](/slides/python-net/de/aspose.slides/ioleembeddeddatainfo)
* Klasse [`IOleObjectFrame`](/slides/python-net/de/aspose.slides/ioleobjectframe)
* Klasse [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)