---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides für C++ API-Referenz
description: "Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn in die ShapeCollection an dem angegebenen Index ein. Der eingebettete Audio wird zur Presentation::get_Audios-Collection hinzugefügt."
type: docs
weight: 300
url: /de/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) Methode

Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn in die ShapeCollection an der angegebenen Position ein. Der eingebettete Audio wird zur [Presentation::get_Audios](../../presentation/get_audios/)-Collection hinzugefügt.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem der Audio-Frame eingefügt wird. |
| x | **float** | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | **float** | Die Breite des neuen Audio-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Audio-Frames in Punkten. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ein Eingabestream, der WAV-Audiodaten zum Einbetten enthält. |

### Rückgabewert

Das neu erstellte [IAudioFrame](../../iaudioframe/).

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) Methode

Erstellt einen neuen Audio-Frame und fügt ihn an der angegebenen Position in die ShapeCollection ein, wobei ein vorhandenes Audio-Objekt aus der [Presentation::get_Audios](../../presentation/get_audios/)-Liste verwendet wird.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem der Audio-Frame eingefügt wird. |
| x | **float** | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | **float** | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | **float** | Die Breite des neuen Audio-Frames in Punkten. |
| height | **float** | Die Höhe des neuen Audio-Frames in Punkten. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Eine [IAudio](../../iaudio/)-Instanz aus der [Presentation::get_Audios](../../presentation/get_audios/)-Collection zum Einbetten. |

### Rückgabewert

Das neu erstellte [IAudioFrame](../../iaudioframe/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudioFrame](../../iaudioframe/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [ShapeCollection](../)
* Klasse [IAudio](../../iaudio/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)