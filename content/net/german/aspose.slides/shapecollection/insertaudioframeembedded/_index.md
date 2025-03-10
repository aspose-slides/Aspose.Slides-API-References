---
title: InsertAudioFrameEmbedded
second_title: Aspose.Slides für .NET-API-Referenz
description: Fügen Sie einen AudioFrame mit eingebetteter Audiodatei ein. Eingebetteter AudiodateiSound kann nur WAV sein.
type: docs
weight: 280
url: /de/aspose.slides/shapecollection/insertaudioframeembedded/
---
## InsertAudioFrameEmbedded(int, float, float, float, float, Stream) {#insertaudioframeembedded_1}

Fügen Sie einen AudioFrame mit eingebetteter Audiodatei ein. Eingebetteter Audiodatei-Sound kann nur WAV sein.

```csharp
public IAudioFrame InsertAudioFrameEmbedded(int index, float x, float y, float width, float height, 
    Stream audio_stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Der nullbasierte Index, an dem der Wert eingefügt werden soll. |
| x | Single | X-Koordinate eines neuen Audioframes. |
| y | Single | Y-Koordinate eines neuen Audiorahmens. |
| width | Single | Breite eines neuen Audioframes. |
| height | Single | Höhe eines neuen Audioframes. |
| audio_stream | Stream | Audiostream. |

### Rückgabewert

Erstelltes AudioFrame-Objekt.

### Siehe auch

* interface [IAudioFrame](../../iaudioframe)
* class [ShapeCollection](../../shapecollection)
* namensraum [Aspose.Slides](../../shapecollection)
* Montage [Aspose.Slides](../../../)

---

## InsertAudioFrameEmbedded(int, float, float, float, float, IAudio) {#insertaudioframeembedded}

Fügt einen AudioFrame mit eingebetteter Audiodatei ein. Es verwendet eine Audiodatei aus der Presentation.Audios-Liste.

```csharp
public IAudioFrame InsertAudioFrameEmbedded(int index, float x, float y, float width, float height, 
    IAudio audio)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Der nullbasierte Index, an dem der Wert eingefügt werden soll. |
| x | Single | X-Koordinate eines neuen Audioframes. |
| y | Single | Y-Koordinate eines neuen Audiorahmens. |
| width | Single | Breite eines neuen Audioframes. |
| height | Single | Höhe eines neuen Audioframes. |
| audio | IAudio | Audio aus der Presentation.Audios-Liste. |

### Rückgabewert

Erstelltes AudioFrame-Objekt.

### Siehe auch

* interface [IAudioFrame](../../iaudioframe)
* interface [IAudio](../../iaudio)
* class [ShapeCollection](../../shapecollection)
* namensraum [Aspose.Slides](../../shapecollection)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
