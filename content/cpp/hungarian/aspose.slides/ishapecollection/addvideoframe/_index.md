---
title: AddVideoFrame()
second_title: Aspose.Slides C++ API hivatkozás
description: Új videókeretet hoz létre, és a alakzatgyűjtemény végére adja hozzá.
type: docs
weight: 170
url: /hu/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) metódus

Új videókeretet hoz létre, és a alakzatgyűjtemény végére adja hozzá.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új videókeret x koordinátája pontban. |
| y | **float** | Az új videókeret y koordinátája pontban. |
| width | **float** | Az új videókeret szélessége pontban. |
| height | **float** | Az új videókeret magassága pontban. |
| fname | [System::String](../../../system/string/) | A beágyazandó videófájl útvonala vagy neve. |

### Visszatérési érték

Az újonnan létrehozott [IVideoFrame](../../ivideoframe/).

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) metódus

Új videókeretet hoz létre, és a alakzatgyűjtemény végére adja hozzá.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új videókeret x koordinátája pontban. |
| y | **float** | Az új videókeret y koordinátája pontban. |
| width | **float** | Az új videókeret szélessége pontban. |
| height | **float** | Az új videókeret magassága pontban. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | A [IVideo](../../ivideo/) a videókeretben beágyazandó. |

### Visszatérési érték

Az újonnan létrehozott [IVideoFrame](../../ivideoframe/).

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IVideoFrame](../../ivideoframe/)
* Osztály [String](../../../system/string/)
* Osztály [IShapeCollection](../)
* Osztály [IVideo](../../ivideo/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)