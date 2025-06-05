---
title: TrimFromEnd
second_title: Aspose.Slides para .NET Referencia de API
description: Especifica la duración del tiempo que se eliminará del final del medio durante la reproducción en milisegundos. Lectura/escritura Simple.
type: docs
weight: 150
url: /es/aspose.slides/audioframe/trimfromend/
---

## Propiedad AudioFrame.TrimFromEnd

Especifica la duración del tiempo que se eliminará del final del medio durante la reproducción, en milisegundos. Lectura/escritura Simple.

```csharp
public float TrimFromEnd { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAudio audio = pres.Audios.AddAudio(File.ReadAllBytes("sampleaudio.mp3"));
    IAudioFrame audioFrame = pres.Slides[0].Shapes.AddAudioFrameEmbedded(50, 50, 100, 100, audio);

    // Establecer el tiempo de recorte final 2 segundos
    audioFrame.TrimFromEnd = 2000f;
}
```

### Ver También

* clase [AudioFrame](../../audioframe)
* espacio de nombres [Aspose.Slides](../../audioframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->