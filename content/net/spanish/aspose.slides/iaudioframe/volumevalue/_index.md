---
title: VolumeValue
second_title: Aspose.Slides para .NET API Reference
description: Devuelve o establece el volumen de audio en porcentajes. Lectura/escritura Single.
type: docs
weight: 190
url: /es/aspose.slides/iaudioframe/volumevalue/
---

## Propiedad IAudioFrame.VolumeValue

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

    // Establecer el volumen de audio en 85%
    audioFrame.VolumeValue = 85f;

    pres.Save("AudioFrameValue_out.pptx", SaveFormat.Pptx);
}
```

### Ver También

* interfaz [IAudioFrame](../../iaudioframe)
* espacio de nombres [Aspose.Slides](../../iaudioframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->