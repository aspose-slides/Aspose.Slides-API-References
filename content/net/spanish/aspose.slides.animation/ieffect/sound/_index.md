---
title: Sound
second_title: Aspose.Sildes para la referencia de la API de .NET
description: Sonido embebido definido para el efecto. Leer/escribir IAudioaspose.slides/iaudio.
type: docs
weight: 80
url: /es/aspose.slides.animation/ieffect/sound/
---

## Propiedad IEffect.Sound

Sonido embebido definido para el efecto. Leer/escribir [`IAudio`](../../../aspose.slides/iaudio).

```csharp
public IAudio Sound { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];
    
    // Obtiene la secuencia de efectos para la diapositiva
    ISequence effectsSequence = slide.Timeline.MainSequence;
    
    foreach (IEffect effect in effectsSequence)
    {
        if (effect.Sound == null)
            continue;
        
        // Extrae el sonido del efecto en una matriz de bytes
        byte[] audio = effect.Sound.BinaryData;
    }
}
```

### Véase También

* interfaz [IAudio](../../../aspose.slides/iaudio)
* interfaz [IEffect](../../ieffect)
* espacio de nombres [Aspose.Slides.Animation](../../ieffect)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->