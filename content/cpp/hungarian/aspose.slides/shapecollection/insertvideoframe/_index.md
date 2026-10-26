---
title: InsertVideoFrame()
second_title: Aspose.Slides C++ API referencia
description: Új videókeretet hoz létre, és a megadott indexnél beszúrja az alakzatgyűjteménybe.
type: docs
weight: 222
url: /hu/aspose.slides/shapecollection/insertvideoframe/
---
## ShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) metódus

Létrehoz egy új videókeretet, és a megadott indexnél beilleszti az alakzatgyűjteménybe.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulla alapú index, amelynél be kell szúrni a videókeretet. |
| x | **float** | Az új videókeret x-koordinátája pontban. |
| y | **float** | Az új videókeret y-koordinátája pontban. |
| width | **float** | Az új videókeret szélessége pontban. |
| height | **float** | Az új videókeret magassága pontban. |
| fname | [System::String](../../../system/string/) | A beágyazandó videofájl elérési útja vagy neve. |

### Visszatérési érték

Az újonnan létrehozott [IVideoFrame](../../ivideoframe/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IVideoFrame](../../ivideoframe/)
* Osztály [String](../../../system/string/)
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)