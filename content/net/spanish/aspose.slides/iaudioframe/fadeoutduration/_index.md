---
title: FadeOutDuration
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica la duración en milisegundos para el desvanecimiento final del medio. Lectura/escritura Single.
type: docs
weight: 90
url: /es/aspose.slides/iaudioframe/fadeoutduration/
---

## Propiedad IAudioFrame.FadeOutDuration

Especifica la duración en milisegundos para el desvanecimiento final del medio. Lectura/escritura Single.

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

    // Establecer la duración del desvanecimiento final en 500ms
    audioFrame.FadeOutDuration = 500f;

    pres.Save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interfaz [IAudioFrame](../../iaudioframe)
* espacio de nombres [Aspose.Slides](../../iaudioframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->