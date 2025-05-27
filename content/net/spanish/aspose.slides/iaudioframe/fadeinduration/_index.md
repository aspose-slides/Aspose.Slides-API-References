---
title: FadeInDuration
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica la duración del tiempo para la aparición inicial del medio en milisegundos. Lectura/escritura Single.
type: docs
weight: 80
url: /es/aspose.slides/iaudioframe/fadeinduration/
---

## Propiedad IAudioFrame.FadeInDuration

Especifica la duración del tiempo para la aparición inicial del medio en milisegundos. Lectura/escritura Single.

```csharp
public float FadeInDuration { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    // Agregar Marco de Audio
    IAudio audio = pres.Audios.AddAudio(File.ReadAllBytes("sampleaudio.mp3"));
    IAudioFrame audioFrame = pres.Slides[0].Shapes.AddAudioFrameEmbedded(50, 50, 100, 100, audio);

    // Establecer la duración de la aparición inicial en 200ms
    audioFrame.FadeInDuration = 200f;

    pres.Save("AudioFrameFade_out.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interfaz [IAudioFrame](../../iaudioframe)
* espacio de nombres [Aspose.Slides](../../iaudioframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->