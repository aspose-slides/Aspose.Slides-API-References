---
title: TrimFromStart
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica la duración del tiempo que se eliminará del principio del medio durante la reproducción en milisegundos. Lectura/escritura Single.
type: docs
weight: 160
url: /es/aspose.slides/audioframe/trimfromstart/
---

## Propiedad AudioFrame.TrimFromStart

Especifica la duración del tiempo que se eliminará del principio del medio durante la reproducción, en milisegundos. Lectura/escritura Single.

```csharp
public float TrimFromStart { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAudio audio = pres.Audios.AddAudio(File.ReadAllBytes("sampleaudio.mp3"));
    IAudioFrame audioFrame = pres.Slides[0].Shapes.AddAudioFrameEmbedded(50, 50, 100, 100, audio);

    // Establecer el tiempo de recorte de inicio en 1.5 segundos
    audioFrame.TrimFromStart = 1500f;
}
```

### Ver También

* clase [AudioFrame](../../audioframe)
* espacio de nombres [Aspose.Slides](../../audioframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->