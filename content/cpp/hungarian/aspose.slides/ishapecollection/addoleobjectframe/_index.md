---
title: AddOleObjectFrame()
second_title: Aspose.Slides for C++ API Referencia
description: Új OLE objektumkeretet hoz létre, és a shape collection végére adja hozzá.
type: docs
weight: 66
url: /hu/aspose.slides/ishapecollection/addoleobjectframe/
---
## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metódus


Új OLE objektumkeretet hoz létre, és a shape collection végére adja hozzá.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új OLE keret x-koordinátája pontban. |
| y | **float** | Az új OLE keret y-koordinátája pontban. |
| width | **float** | Az új OLE keret szélessége pontban. |
| height | **float** | Az új OLE keret magassága pontban. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | A beágyazott OLE adatinformáció ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Visszatérési érték

Az újonnan létrehozott [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::AddOleObjectFrame(float, float, float, float, System::String, System::String) metódus


Új OLE objektumkeretet hoz létre, és a shape collection végére adja hozzá.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::AddOleObjectFrame(float x, float y, float width, float height, System::String className, System::String path)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új OLE keret x-koordinátája pontban. |
| y | **float** | Az új OLE keret y-koordinátája pontban. |
| width | **float** | Az új OLE keret szélessége pontban. |
| height | **float** | Az új OLE keret magassága pontban. |
| className | [System::String](../../../system/string/) | Az OLE objektum osztályneve. |
| path | [System::String](../../../system/string/) | Az összekapcsolt fájl elérési útja. |

### Visszatérési érték

Az újonnan létrehozott [IOleObjectFrame](../../ioleobjectframe/).
## Megjegyzések



Ez az útvonal változatlanul tárolódik a prezentációban. Ha relatív útvonal van megadva, a fájl nem lesz elérhető, ha a prezentációt egy másik könyvtárból nyitják meg.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IOleObjectFrame](../../ioleobjectframe/)
* Osztály [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Osztály [IShapeCollection](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)