---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn am Ende der Shape-Sammlung hinzu. Die eingebettete Audiodatei wird zur Presentation.Audios-Sammlung hinzugefügt.
type: docs
weight: 248
url: /de/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) Methode

Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn am Ende der Shape-Sammlung hinzu. Die eingebettete Audiodatei wird zur Presentation.Audios-Sammlung hinzugefügt.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen Audio-Frames, angegeben in Punkten. |
| y | **float** | Die y-Koordinate des neuen Audio-Frames, angegeben in Punkten. |
| width | **float** | Die Breite des neuen Audio-Frames, angegeben in Punkten. |
| height | **float** | Die Höhe des neuen Audio-Frames, angegeben in Punkten. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ein Eingabestream, der WAV-Audiodaten zum Einbetten enthält. |

### Rückgabewert

Der neu erstellte [IAudioFrame](../../iaudioframe/).

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) Methode

Erstellt einen neuen Audio-Frame und fügt ihn am Ende der Shape-Sammlung hinzu, indem ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate des neuen Audio-Frames, angegeben in Punkten. |
| y | **float** | Die y-Koordinate des neuen Audio-Frames, angegeben in Punkten. |
| width | **float** | Die Breite des neuen Audio-Frames, angegeben in Punkten. |
| height | **float** | Die Höhe des neuen Audio-Frames, angegeben in Punkten. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Eine [IAudio](../../iaudio/)-Instanz aus der Presentation.Audios-Sammlung. |

### Rückgabewert

Der neu erstellte [IAudioFrame](../../iaudioframe/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [IShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)