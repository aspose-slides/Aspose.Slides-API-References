---
title: TrimFromEnd
second_title: Referencia de API de Aspose.Sildes para .NET
description: Especifica la duración del tiempo que se debe eliminar del final del medio durante la reproducción en milisegundos. Lectura/escritura Simple.
type: docs
weight: 150
url: /es/aspose.slides/audioframe/trimfromend/
---

## Propiedad AudioFrame.TrimFromEnd

Especifica la duración del tiempo que se debe eliminar del final del medio durante la reproducción, en milisegundos. Lectura/escritura Simple.

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

    // Establecer el tiempo de recorte final en 2 segundos
    audioFrame.TrimFromEnd = 2000f;
}
```

### Véase También

* clase [AudioFrame](../../audioframe)
* espacio de nombres [Aspose.Slides](../../audioframe)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->