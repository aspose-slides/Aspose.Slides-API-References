---
title: AddAudioFrameLinked()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy új audio keretet, amely egy külső audio fájlra hivatkozik, és a shape gyűjtemény végéhez adja hozzá.
type: docs
weight: 222
url: /hu/aspose.slides/ishapecollection/addaudioframelinked/
---
## IShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) metódus

Létrehoz egy új audio keretet, amely egy külső audio fájlra hivatkozik, és a shape gyűjtemény végéhez adja hozzá.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új audio keret x-koordinátája pontban. |
| y | **float** | Az új audio keret y-koordinátája pontban. |
| width | **float** | Az új audio keret szélessége pontban. |
| height | **float** | Az új audio keret magassága pontban. |
| fname | [System::String](../../../system/string/) | A külső audio fájl elérési útja vagy neve, amelyre hivatkozni kell. |

### Visszatérési érték

Az újonnan létrehozott [IAudioFrame](../../iaudioframe/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudioFrame](../../iaudioframe/)
* Osztály [String](../../../system/string/)
* Osztály [IShapeCollection](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)