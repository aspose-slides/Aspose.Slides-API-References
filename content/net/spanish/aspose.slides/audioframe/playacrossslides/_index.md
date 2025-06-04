---
title: PlayAcrossSlides
second_title: Referencia de API de Aspose.Slides para .NET
description: Determina si el audio se reproduce a través de las diapositivas. Booleano de lectura/escritura.
type: docs
weight: 110
url: /es/aspose.slides/audioframe/playacrossslides/
---

## AudioFrame.PlayAcrossSlides property

Determina si el audio se reproduce a través de las diapositivas. Booleano de lectura/escritura.

```csharp
public bool PlayAcrossSlides { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide slide = pres.Slides[0];

    // Agregar Marco de Audio
    IAudioFrame audioFrame = slide.Shapes.AddAudioFrameLinked(50, 50, 100, 100, "sampleaudio.wav");

    // Configurar Audio para que se reproduzca a través de las diapositivas
    audioFrame.PlayAcrossSlides = true;

    // Configurar Audio para que se rebobine automáticamente al inicio después de reproducir
    audioFrame.RewindAudio = true;

    pres.Save("AudioFrame_out.pptx", SaveFormat.Pptx);
}
```

### Véase también

* class [AudioFrame](../../audioframe)
* namespace [Aspose.Slides](../../audioframe)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->
