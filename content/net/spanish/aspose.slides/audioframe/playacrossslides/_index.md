---
title: PlayAcrossSlides
second_title: Aspose.Sildes para .NET Referencia de API
description: Determina si el audio se está reproduciendo a través de las diapositivas. Booleano de lectura/escritura.
type: docs
weight: 110
url: /es/aspose.slides/audioframe/playacrossslides/
---

## Propiedad AudioFrame.PlayAcrossSlides

Determina si el audio se está reproduciendo a través de las diapositivas. Booleano de lectura/escritura.

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

    // Configurar audio para que se reproduzca a través de las diapositivas
    audioFrame.PlayAcrossSlides = true;

    // Configurar audio para que se rebobine automáticamente al inicio después de reproducirse
    audioFrame.RewindAudio = true;

    pres.Save("AudioFrame_out.pptx", SaveFormat.Pptx);
}
```

### Véase También

* clase [AudioFrame](../../audioframe)
* espacio de nombres [Aspose.Slides](../../audioframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->