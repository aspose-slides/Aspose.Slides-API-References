---
title: InsertOleObjectFrame()
second_title: Aspose.Slides C++ API referencia
description: Új OLE objektum keretet hoz létre, és a megadott indexnél beilleszti a alakzatgyűjteménybe.
type: docs
weight: 79
url: /hu/aspose.slides/ishapecollection/insertoleobjectframe/
---
## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::SharedPtr\<IOleEmbeddedDataInfo\>) metódus


Új OLE objektum keretet hoz létre, és a megadott indexnél beilleszti a alakzatgyűjteménybe.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::SharedPtr<IOleEmbeddedDataInfo> dataInfo)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az a nullánál kezdődő index, amelynél az OLE objektum keretet be kell illeszteni. |
| x | **float** | Az új OLE keret x-koordinátája pontban. |
| y | **float** | Az új OLE keret y-koordinátája pontban. |
| width | **float** | Az új OLE keret szélessége pontban. |
| height | **float** | Az új OLE keret magassága pontban. |
| dataInfo | [System::SharedPtr](../../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)\> | A beágyazott OLE adatinformáció ([IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)). |

### Visszatérési érték

Az újonnan létrehozott [IOleObjectFrame](../../ioleobjectframe/).

## IShapeCollection::InsertOleObjectFrame(int32_t, float, float, float, float, System::String, System::String) metódus


Új OLE objektum keretet hoz létre, és a megadott indexnél beilleszti a alakzatgyűjteménybe.

```cpp
virtual System::SharedPtr<IOleObjectFrame> Aspose::Slides::IShapeCollection::InsertOleObjectFrame(int32_t index, float x, float y, float width, float height, System::String className, System::String path)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az a nullánál kezdődő index, amelynél az OLE objektum keretet be kell illeszteni. |
| x | **float** | Az új OLE keret x-koordinátája pontban. |
| y | **float** | Az új OLE keret y-koordinátája pontban. |
| width | **float** | Az új OLE keret szélessége pontban. |
| height | **float** | Az új OLE keret magassága pontban. |
| className | [System::String](../../../system/string/) | Az OLE objektum osztályneve. |
| path | [System::String](../../../system/string/) | A hivatkozott fájl elérési útja. |

### Visszatérési érték

Az újonnan létrehozott [IOleObjectFrame](../../ioleobjectframe/).

## Megjegyzések



Ez az útvonal szó szerint tárolódik a prezentációban. Ha relatív útvonal van megadva, a fájl nem lesz elérhető, ha a prezentációt egy másik könyvtárból nyitják meg.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IOleObjectFrame](../../ioleobjectframe/)
* Osztály [IOleEmbeddedDataInfo](../../ioleembeddeddatainfo/)
* Osztály [IShapeCollection](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)