---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides C++ API-referencia
description: Létrehoz egy új audio keretet beágyazott WAV fájllal, és a forma gyűjtemény végére adja hozzá. A beágyazott hang a Presentation.Audios gyűjteményhez kerül hozzáadásra.
type: docs
weight: 248
url: /hu/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) módszer


Létrehoz egy új audio keretet beágyazott WAV fájllal, és a forma gyűjtemény végére adja hozzá. A beágyazott hang a Presentation.Audios gyűjteményhez kerül hozzáadásra.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új audio keret x-koordinátája pontokban. |
| y | **float** | Az új audio keret y-koordinátája pontokban. |
| width | **float** | Az új audio keret szélessége pontokban. |
| height | **float** | Az új audio keret magassága pontokban. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Egy bemeneti adatfolyam, amely beágyazandó WAV hang adatot tartalmaz. |

### Visszatérési érték

Az újonnan létrehozott [IAudioFrame](../../iaudioframe/).

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) módszer


Létrehoz egy új audio keretet, és a forma gyűjtemény végére adja hozzá a Presentation.Audios listából származó meglévő audio objektum használatával.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új audio keret x-koordinátája pontokban. |
| y | **float** | Az új audio keret y-koordinátája pontokban. |
| width | **float** | Az új audio keret szélessége pontokban. |
| height | **float** | Az új audio keret magassága pontokban. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Egy [IAudio](../../iaudio/) példány a Presentation.Audios gyűjteményből. |

### Visszatérési érték

Az újonnan létrehozott [IAudioFrame](../../iaudioframe/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAudioFrame](../../iaudioframe/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [IShapeCollection](../)
* Osztály [IAudio](../../iaudio/)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)