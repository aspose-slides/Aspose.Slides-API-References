---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides C++ API Referencia
description: Létrehoz egy új hangkeretet, amely egy külső hangfájlra hivatkozik, és beszúrja azt a megadott indexnél az alakzatgyűjteménybe.
type: docs
weight: 274
url: /hu/aspose.slides/shapecollection/insertaudioframelinked/
---
## ShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) metódus

Új hangkeretet hoz létre, amely külső hangfájlra hivatkozik, és a megadott indexnél beszúrja a alakzatgyűjteménybe.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az a nulláról számított index, amelynél be kell szúrni a hangkeretet. |
| x | **float** | Az új hangkeret x-koordinátája pontban. |
| y | **float** | Az új hangkeret y-koordinátája pontban. |
| width | **float** | Az új hangkeret szélessége pontban. |
| height | **float** | Az új hangkeret magassága pontban. |
| fname | [System::String](../../../system/string/) | A külső hangfájl elérési útja vagy neve, amelyre hivatkozni kell. |

### Visszatérési érték

Az újonnan létrehozott [IAudioFrame](../../iaudioframe/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudioFrame](../../iaudioframe/)
* Osztály [String](../../../system/string/)
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)