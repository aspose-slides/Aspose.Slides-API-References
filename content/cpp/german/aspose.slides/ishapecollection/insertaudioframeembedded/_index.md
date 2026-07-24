---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues Audio-Frame mit einer eingebetteten WAV-Datei und fügt es an der angegebenen Position in die Shape-Collection ein. Das eingebettete Audio wird zur Presentation.Audios-Collection hinzugefügt.
type: docs
weight: 261
url: /de/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) Methode


Erstellt ein neues Audio-Frame mit einer eingebetteten WAV-Datei und fügt es an der angegebenen Position in die Shape-Collection ein. Das eingebettete Audio wird zur Presentation.Audios-Collection hinzugefügt.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem das Audio-Frame eingefügt wird. |
| x | **float** | Die x-Koordinate des neuen Audio-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Audio-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Audio-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Audio-Frames, in Punkten. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ein Eingabestream, der WAV-Audiodaten zum Einbetten enthält. |

### Rückgabewert

Das neu erstellte [IAudioFrame](../../iaudioframe/).

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) Methode


Erstellt ein neues Audio-Frame und fügt es an der angegebenen Position in die Shape-Collection ein, indem ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem das Audio-Frame eingefügt wird. |
| x | **float** | Die x-Koordinate des neuen Audio-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des neuen Audio-Frames, in Punkten. |
| width | **float** | Die Breite des neuen Audio-Frames, in Punkten. |
| height | **float** | Die Höhe des neuen Audio-Frames, in Punkten. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Eine [IAudio](../../iaudio/)-Instanz aus der Presentation.Audios-Collection zum Einbetten. |

### Rückgabewert

Das neu erstellte [IAudioFrame](../../iaudioframe/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAudioFrame](../../iaudioframe/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [IShapeCollection](../)
* Klasse [IAudio](../../iaudio/)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)