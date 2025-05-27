---
title: TrimFromEnd
second_title: Referencia de la API Aspose.Sildes para .NET
description: Especifica la duración del tiempo que se debe eliminar del final del medio durante la reproducción, en milisegundos. Lectura/escritura de tipo Single.
type: docs
weight: 160
url: /es/aspose.slides/iaudioframe/trimfromend/
---

## Propiedad IAudioFrame.TrimFromEnd

Especifica la duración del tiempo que se debe eliminar del final del medio durante la reproducción, en milisegundos. Lectura/escritura de tipo Single.

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

### Ver también

* interfaz [IAudioFrame](../../iaudioframe)
* espacio de nombres [Aspose.Slides](../../iaudioframe)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->