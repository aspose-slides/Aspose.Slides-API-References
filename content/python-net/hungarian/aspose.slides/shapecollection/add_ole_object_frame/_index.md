---
title: add_ole_object_frame method
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozása
description: 
type: docs
url: /hu/aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Új OLE objektumkeretet hoz létre, és a alakzatgyűjtemény végéhez adja hozzá.

### Visszatérési érték

Az újonnan létrehozott [`IOleObjectFrame`](/slides/python-net/hu/aspose.slides/ioleobjectframe).

```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új OLE keret x-koordinátája, pontban. |
| y | **float** | Az új OLE keret y-koordinátája, pontban. |
| width | **float** | Az új OLE keret szélessége, pontban. |
| height | **float** | Az új OLE keret magassága, pontban. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo) | Az beágyazott OLE adatokra vonatkozó információ ([`IOleEmbeddedDataInfo`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo)). |

## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Új OLE objektumkeretet hoz létre, és a alakzatgyűjtemény végéhez adja hozzá.

### Visszatérési érték

Az újonnan létrehozott [`IOleObjectFrame`](/slides/python-net/hu/aspose.slides/ioleobjectframe).

```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új OLE keret x-koordinátája, pontban. |
| y | **float** | Az új OLE keret y-koordinátája, pontban. |
| width | **float** | Az új OLE keret szélessége, pontban. |
| height | **float** | Az új OLE keret magassága, pontban. |
| class_name | **str** | Az OLE objektum osztályneve. |
| path | **str** | A hivatkozott fájl elérési útja. <br/><br/>Ez az útvonal a prezentációban változatlanul tárolódik.<br/><br/>            Ha relatív útvonal van megadva, a fájl a prezentáció másik könyvtárból történő megnyitásakor nem lesz elérhető.<br/><br/>            |

### Lásd még
* osztály [`IOleEmbeddedDataInfo`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo)
* osztály [`IOleObjectFrame`](/slides/python-net/hu/aspose.slides/ioleobjectframe)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)