---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy új hangkeretet beágyazott WAV fájllal, és a megadott indexnél beszúrja a forma gyűjteménybe. A beágyazott hang a Presentation.Audios gyűjteményhez kerül hozzáadásra.
type: docs
weight: 261
url: /hu/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metódus


Új hangkeretet hoz létre egy beágyazott WAV fájl-val, és a megadott indexnél beszúrja a forma gyűjteménybe. A beágyazott hang a Presentation.Audios gyűjteményhez kerül hozzáadásra.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulla alapú index, amelynél a hangkeretet be kell szúrni. |
| x | **float** | Az új hangkeret x-koordinátája pontban. |
| y | **float** | Az új hangkeret y-koordinátája pontban. |
| width | **float** | Az új hangkeret szélessége pontban. |
| height | **float** | Az új hangkeret magassága pontban. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Egy bemeneti adatfolyam, amely WAV hangadatokat tartalmaz a beágyazáshoz. |

### Visszatérési érték

Az újonnan létrehozott [IAudioFrame](../../iaudioframe/).

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) metódus


Új hangkeretet hoz létre, és a megadott indexnél a forma gyűjteménybe illeszti a Presentation.Audios listából származó meglévő hangobjektum felhasználásával.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulla alapú index, amelynél a hangkeretet be kell szúrni. |
| x | **float** | Az új hangkeret x-koordinátája pontban. |
| y | **float** | Az új hangkeret y-koordinátája pontban. |
| width | **float** | Az új hangkeret szélessége pontban. |
| height | **float** | Az új hangkeret magassága pontban. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | A Presentation.Audios gyűjteményből származó [IAudio](../../iaudio/) példány a beágyazáshoz. |

### Visszatérési érték

Az újonnan létrehozott [IAudioFrame](../../iaudioframe/).

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudioFrame](../../iaudioframe/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [IShapeCollection](../)
* Osztály [IAudio](../../iaudio/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)