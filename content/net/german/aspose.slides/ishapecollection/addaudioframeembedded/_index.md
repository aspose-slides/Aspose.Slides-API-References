---
title: AddAudioFrameEmbedded
second_title: Aspose.Sildes für .NET API Referenz
description: Fügt einer Sammlung ein neues Audio-Frame mit eingebetteter Audiodatei hinzu. Die eingebettete Audiodatei kann nur im WAV-Format vorliegen. Es fügt neues Audio zur Liste Presentation.Audios hinzu.
type: docs
weight: 40
url: /de/aspose.slides/ishapecollection/addaudioframeembedded/
---

## AddAudioFrameEmbedded(float, float, float, float, Stream) {#addaudioframeembedded_1}

Fügt einer Sammlung ein neues Audio-Frame mit eingebetteter Audiodatei hinzu. Die eingebettete Audiodatei kann nur im WAV-Format vorliegen. Es fügt neues Audio zur Liste Presentation.Audios hinzu.

```csharp
public IAudioFrame AddAudioFrameEmbedded(float x, float y, float width, float height, 
    Stream audio_stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Single | X-Koordinate eines neuen Audio-Frames. |
| y | Single | Y-Koordinate eines neuen Audio-Frames. |
| width | Single | Breite eines neuen Audio-Frames. |
| height | Single | Höhe eines neuen Audio-Frames. |
| audio_stream | Stream | Eingabe-Stream mit Audiodaten. |

### Rückgabewert

Erstelltes AudioFrame-Objekt.

### Siehe auch

* Schnittstelle [IAudioFrame](../../iaudioframe)
* Schnittstelle [IShapeCollection](../../ishapecollection)
* Namespace [Aspose.Slides](../../ishapecollection)
* Assembly [Aspose.Slides](../../../)

---

## AddAudioFrameEmbedded(float, float, float, float, IAudio) {#addaudioframeembedded}

Fügt einer Sammlung ein neues Audio-Frame mit eingebetteter Audiodatei hinzu. Es verwendet die Audiodatei aus der Liste Presentation.Audios.

```csharp
public IAudioFrame AddAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Single | X-Koordinate eines neuen Audio-Frames. |
| y | Single | Y-Koordinate eines neuen Audio-Frames. |
| width | Single | Breite eines neuen Audio-Frames. |
| height | Single | Höhe eines neuen Audio-Frames. |
| audio | IAudio | Audio aus der Liste Presentation.Audios. |

### Rückgabewert

Erstelltes AudioFrame-Objekt.

### Siehe auch

* Schnittstelle [IAudioFrame](../../iaudioframe)
* Schnittstelle [IAudio](../../iaudio)
* Schnittstelle [IShapeCollection](../../ishapecollection)
* Namespace [Aspose.Slides](../../ishapecollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->