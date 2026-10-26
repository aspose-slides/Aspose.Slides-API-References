---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides C++ API Referenciája
description: "Létrehoz egy új hangkeretet beágyazott WAV-fájllal, és beszúrja a shape collection-be a megadott indexen. A beágyazott hang hozzáadódik a Presentation::get_Audios gyűjteményhez."
type: docs
weight: 300
url: /hu/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metódus

Létrehoz egy új hangkeretet beágyazott WAV-fájllal, és beszúrja a shape collection-be a megadott indexen. A beágyazott hang hozzáadódik a [Presentation::get_Audios](../../presentation/get_audios/) gyűjteményhez.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullától kezdődő index, ahol a hangkeretet be kell szúrni. |
| x | **float** | Az új hangkeret x-koordinátája pontban. |
| y | **float** | Az új hangkeret y-koordinátája pontban. |
| width | **float** | Az új hangkeret szélessége pontban. |
| height | **float** | Az új hangkeret magassága pontban. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Egy bemeneti adatfolyam, amely beágyazandó WAV hangadatot tartalmaz. |

### Visszatérési érték

Az újonnan létrehozott [IAudioFrame](../../iaudioframe/).

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) metódus

Létrehoz egy új hangkeretet, és beszúrja a shape collection-be a megadott indexen egy meglévő hangobjektum használatával a [Presentation::get_Audios](../../presentation/get_audios/) listából.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullától kezdődő index, ahol a hangkeretet be kell szúrni. |
| x | **float** | Az új hangkeret x-koordinátája pontban. |
| y | **float** | Az új hangkeret y-koordinátája pontban. |
| width | **float** | Az új hangkeret szélessége pontban. |
| height | **float** | Az új hangkeret magassága pontban. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Egy [IAudio](../../iaudio/) példány a [Presentation::get_Audios](../../presentation/get_audios/) gyűjteményből a beágyazáshoz. |

### Visszatérési érték

Az újonnan létrehozott [IAudioFrame](../../iaudioframe/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudioFrame](../../iaudioframe/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [ShapeCollection](../)
* Osztály [IAudio](../../iaudio/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)