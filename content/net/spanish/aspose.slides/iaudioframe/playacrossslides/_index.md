---
title: PlayAcrossSlides
second_title: Referencia de API de Aspose.Slides para .NET
description: Determina si un audio se está reproduciendo a través de las diapositivas. Booleano de lectura/escritura.
type: docs
weight: 120
url: /es/aspose.slides/iaudioframe/playacrossslides/
---

## Propiedad IAudioFrame.PlayAcrossSlides

Determina si un audio se está reproduciendo a través de las diapositivas. Booleano de lectura/escritura.

```csharp
public bool PlayAcrossSlides { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide slide = pres.Slides[0];

    // Agregar marco de audio
    IAudioFrame audioFrame = slide.Shapes.AddAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");

    // Configurar el audio para reproducirse a través de las diapositivas
    audioFrame.PlayAcrossSlides = true;

    // Configurar el audio para retroceder automáticamente al inicio después de reproducirse
    audioFrame.RewindAudio = true;

    pres.Save("AudioFrame_out.pptx", SaveFormat.Pptx);
}
```

### Véase También

* interfaz [IAudioFrame](../../iaudioframe)
* espacio de nombres [Aspose.Slides](../../iaudioframe)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->