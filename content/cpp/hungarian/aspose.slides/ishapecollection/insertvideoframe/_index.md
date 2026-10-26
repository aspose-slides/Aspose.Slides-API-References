---
title: InsertVideoFrame()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy új videokeretet, és a megadott indexnél beszúrja az alakzatgyűjteménybe.
type: docs
weight: 183
url: /hu/aspose.slides/ishapecollection/insertvideoframe/
---
## IShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) method


Létrehoz egy új videokeretet, és beszúrásra kerül a alakzatgyűjteménybe a megadott indexnél.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulla-alapú index, ahová a videokeret be lesz szúrva. |
| x | **float** | Az új videokeret x-koordinátája pontban. |
| y | **float** | Az új videokeret y-koordinátája pontban. |
| width | **float** | Az új videokeret szélessége pontban. |
| height | **float** | Az új videokeret magassága pontban. |
| fname | [System::String](../../../system/string/) | A beágyazandó videofájl elérési útja vagy neve. |

### Visszatérési érték

Az újonnan létrehozott [IVideoFrame](../../ivideoframe/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IVideoFrame](../../ivideoframe/)
* Osztály [String](../../../system/string/)
* Osztály [IShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)