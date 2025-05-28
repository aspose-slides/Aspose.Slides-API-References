---
title: TrimFromStart
second_title: Referencia de la API de Aspose.Slides para .NET
description: Especifica la duración del tiempo a eliminar desde el comienzo del medio durante la reproducción en milisegundos. Lectura/escritura Single.
type: docs
weight: 170
url: /es/aspose.slides/iaudioframe/trimfromstart/
---

## Propiedad IAudioFrame.TrimFromStart

Especifica la duración del tiempo a eliminar desde el comienzo del medio durante la reproducción, en milisegundos. Lectura/escritura Single.

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

### Véase también

* interfaz [IAudioFrame](../../iaudioframe)
* espacio de nombres [Aspose.Slides](../../iaudioframe)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->