---
title: RewindAudio
second_title: Referencia de API de Aspose.Slides para .NET
description: Determina si un audio se rebobina automáticamente al inicio después de reproducirse. Booleano de lectura/escritura.
type: docs
weight: 150
url: /es/aspose.slides/iaudioframe/rewindaudio/
---

## Propiedad IAudioFrame.RewindAudio

Determina si un audio se rebobina automáticamente al inicio después de reproducirse. Booleano de lectura/escritura.

```csharp
public bool RewindAudio { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide slide = pres.Slides[0];

    // Agregar marco de audio
    IAudioFrame audioFrame = slide.Shapes.AddAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");

    // Configurar audio para reproducirse en las diapositivas
    audioFrame.PlayAcrossSlides = true;

    // Configurar audio para rebobinar automáticamente al inicio después de reproducirse
    audioFrame.RewindAudio = true;

    pres.Save("AudioFrame_out.pptx", SaveFormat.Pptx);
}
```

### Vea También

* interfaz [IAudioFrame](../../iaudioframe)
* espacio de nombres [Aspose.Slides](../../iaudioframe)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->