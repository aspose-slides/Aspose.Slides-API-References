---
title: add_ole_object_frame method
second_title: Aspose.Slides a .NET API hivatkozásán keresztül a Pythonhoz
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Új OLE objektumkeretet hoz létre, és hozzáadja a forma gyűjtemény végéhez.

### Visszatér

Az újonnan létrehozott [`IOleObjectFrame`](/slides/python-net/hu/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új OLE keret x-koordinátája pontokban. |
| y | **float** | Az új OLE keret y-koordinátája pontokban. |
| width | **float** | Az új OLE keret szélessége pontokban. |
| height | **float** | Az új OLE keret magassága pontokban. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo) | A beágyazott OLE adat információ ([`IOleEmbeddedDataInfo`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Új OLE objektumkeretet hoz létre, és hozzáadja a forma gyűjtemény végéhez.

### Visszatér

Az újonnan létrehozott [`IOleObjectFrame`](/slides/python-net/hu/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| x | **float** | Az új OLE keret x-koordinátája pontokban. |
| y | **float** | Az új OLE keret y-koordinátája pontokban. |
| width | **float** | Az új OLE keret szélessége pontokban. |
| height | **float** | Az új OLE keret magassága pontokban. |
| class_name | **str** | Az OLE objektum osztályneve. |
| path | **str** | A linkelt fájl elérési útja. <br/><br/>Ez az elérési út szó szerint tárolódik a prezentációban.<br/><br/>            Ha relatív útvonal van megadva, a fájl nem lesz elérhető a prezentáció megnyitásakor<br/><br/>            különböző könyvtárból. |



### Lásd még
* osztály [`IOleEmbeddedDataInfo`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo)
* osztály [`IOleObjectFrame`](/slides/python-net/hu/aspose.slides/ioleobjectframe)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)