---
title: insert_ole_object_frame method
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Új OLE objektumkeretet hoz létre, és a megadott indexnél beilleszti a formák gyűjteményébe.

### Visszatér

Az újonnan létrehozott [`IOleObjectFrame`](/slides/python-net/hu/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Az a nullától számolt index, amelynél be kell illeszteni az OLE objektumkeretet. |
| x | **float** | Az új OLE keret x-koordinátája pontban. |
| y | **float** | Az új OLE keret y-koordinátája pontban. |
| width | **float** | Az új OLE keret szélessége pontban. |
| height | **float** | Az új OLE keret magassága pontban. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo) | A beágyazott OLE adatinformáció ([`IOleEmbeddedDataInfo`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Új OLE objektumkeretet hoz létre, és a megadott indexnél beilleszti a formák gyűjteményébe.

### Visszatér

Az újonnan létrehozott OLE objektumkeret.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Az a nullától számolt index, amelynél be kell illeszteni az OLE objektumkeretet. |
| x | **float** | Az új OLE keret x-koordinátája pontban. |
| y | **float** | Az új OLE keret y-koordinátája pontban. |
| width | **float** | Az új OLE keret szélessége pontban. |
| height | **float** | Az új OLE keret magassága pontban. |
| class_name | **str** | Az OLE objektum osztályneve. |
| path | **str** | A hivatkozott fájl elérési útja. <br/><br/>Ez az útvonal szó szerint tárolódik a prezentációban.<br/><br/>            Ha relatív útvonal van megadva, a fájl elérhetetlenné válik, ha a<br/><br/>            prezentációt másik könyvtárból nyitják meg. |



### Lásd még
* osztály [`IOleEmbeddedDataInfo`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo)
* osztály [`IOleObjectFrame`](/slides/python-net/hu/aspose.slides/ioleobjectframe)
* osztály [`ShapeCollection`](/slides/python-net/hu/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)