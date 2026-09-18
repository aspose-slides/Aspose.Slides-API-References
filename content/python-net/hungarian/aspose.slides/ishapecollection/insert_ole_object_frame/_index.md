---
title: insert_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Új OLE objektumkeretet hoz létre, és beszúrja a alakzatgyűjteménybe a megadott indexnél.

### Visszatérési érték

Az újonnan létrehozott [`IOleObjectFrame`](/slides/python-net/hu/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullánál kezdődő index, ahol be kell szúrni az OLE objektumkeretet. |
| x | **float** | Az új OLE keret x-koordinátája pontokban. |
| y | **float** | Az új OLE keret y-koordinátája pontokban. |
| width | **float** | Az új OLE keret szélessége pontokban. |
| height | **float** | Az új OLE keret magassága pontokban. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo) | A beágyazott OLE adatinformáció ([`IOleEmbeddedDataInfo`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Új OLE objektumkeretet hoz létre, és beszúrja a alakzatgyűjteménybe a megadott indexnél.

### Visszatérési érték

Az újonnan létrehozott [`IOleObjectFrame`](/slides/python-net/hu/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | A nullánál kezdődő index, ahol be kell szúrni az OLE objektumkeretet. |
| x | **float** | Az új OLE keret x-koordinátája pontokban. |
| y | **float** | Az új OLE keret y-koordinátája pontokban. |
| width | **float** | Az új OLE keret szélessége pontokban. |
| height | **float** | Az új OLE keret magassága pontokban. |
| class_name | **str** | Az OLE objektum osztályneve. |
| path | **str** | A hivatkozott fájl elérési útja. <br/><br/>Ez az útvonal szó szerint tárolódik a prezentációban.<br/><br/>Ha relatív útvonal van megadva, a fájl nem lesz elérhető, amikor a prezentációt egy másik könyvtárból nyitják meg. |



### Lásd még
* osztály [`IOleEmbeddedDataInfo`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo)
* osztály [`IOleObjectFrame`](/slides/python-net/hu/aspose.slides/ioleobjectframe)
* osztály [`IShapeCollection`](/slides/python-net/hu/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)