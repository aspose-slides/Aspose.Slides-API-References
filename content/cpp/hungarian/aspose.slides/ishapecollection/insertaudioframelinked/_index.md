---
title: InsertAudioFrameLinked()
second_title: Aspose.Slides C++ API hivatkozás
description: Új audio keretet hoz létre, amely egy külső audio fájlra hivatkozik, és a megadott indexnél beszúrja azt az alakzatgyűjteménybe.
type: docs
weight: 235
url: /hu/aspose.slides/ishapecollection/insertaudioframelinked/
---
## IShapeCollection::InsertAudioFrameLinked(int32_t, float, float, float, float, System::String) metódus

Új audio keretet hoz létre, amely külső audio fájlra hivatkozik, és beszúrja azt a alakzatgyűjteménybe a megadott indexnél.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameLinked(int32_t index, float x, float y, float width, float height, System::String fname)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | A nulla alapú index, amelyhez az audio keretet be kell szúrni. |
| x | **float** | Az új audio keret x-koordinátája pontban. |
| y | **float** | Az új audio keret y-koordinátája pontban. |
| width | **float** | Az új audio keret szélessége pontban. |
| height | **float** | Az új audio keret magassága pontban. |
| fname | [System::String](../../../system/string/) | A külső audio fájl útvonala vagy neve, amelyhez linkelni kell. |

### Return Value

Az újonnan létrehozott [IAudioFrame](../../iaudioframe/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudioFrame](../../iaudioframe/)
* Osztály [String](../../../system/string/)
* Osztály [IShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)