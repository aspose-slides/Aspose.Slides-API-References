---
title: FadeOutDuration
second_title: Aspose.Sildes para .NET API Reference
description: Especifica la duración del tiempo para la desvanecimiento final del medio en milisegundos. Lectura/escritura Single.
type: docs
weight: 90
url: /es/aspose.slides/iaudioframe/fadeoutduration/
---

## Propiedad IAudioFrame.FadeOutDuration

Especifica la duración del tiempo para la desvanecimiento final del medio en milisegundos. Lectura/escritura Single.

```csharp
public float FadeOutDuration { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    // Agregar marco de audio
    IAudio audio = pres.Audios.AddAudio(File.ReadAllBytes("sampleaudio.mp3"));
    IAudioFrame audioFrame = pres.Slides[0].Shapes.AddAudioFrameEmbedded(50, 50, 100, 100, audio);

    // Establecer la duración del desvanecimiento final a 500ms
    audioFrame.FadeOutDuration = 500f;

    pres.Save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
}
```

### Véase también

* interfaz [IAudioFrame](../../iaudioframe)
* espacio de nombres [Aspose.Slides](../../iaudioframe)
* ensamblado [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->