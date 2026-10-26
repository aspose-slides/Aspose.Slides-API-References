---
title: AddAudioFrameLinked()
second_title: Aspose.Slides C++ API Referencia
description: Létrehozza az új hangkeretet, amely egy külső hangfájlra hivatkozik, és hozzáadja az alakgyűjtemény végéhez.
type: docs
weight: 261
url: /hu/aspose.slides/shapecollection/addaudioframelinked/
---
## ShapeCollection::AddAudioFrameLinked(float, float, float, float, System::String) metódus


Létrehoz egy új hangkeretet, amely egy külső hangfájlra mutat, és az alakgyűjtemény végéhez adja hozzá.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameLinked(float x, float y, float width, float height, System::String fname) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
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