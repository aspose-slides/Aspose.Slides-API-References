---
title: VolumeValue
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve o establece el volumen de audio en porcentajes. Lectura/escritura Single.
type: docs
weight: 180
url: /es/aspose.slides/audioframe/volumevalue/
---

## Propiedad AudioFrame.VolumeValue

Devuelve o establece el volumen de audio en porcentajes. Lectura/escritura Single.

```csharp
public float VolumeValue { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IAudio audio = pres.Audios.AddAudio(File.ReadAllBytes("sampleaudio.mp3"));
    IAudioFrame audioFrame = pres.Slides[0].Shapes.AddAudioFrameEmbedded(50, 50, 100, 100, audio);

    // Establecer el volumen de audio al 85%
    audioFrame.VolumeValue = 85f;

    pres.Save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
}
```

### Véase también

* clase [AudioFrame](../../audioframe)
* espacio de nombres [Aspose.Slides](../../audioframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->