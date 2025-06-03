---
title: Sound
second_title: Referencia de API de Aspose.Slides para .NET
description: Sonido embebido definido para el efecto. Leer/escribir IAudioaspose.slides/iaudio.
type: docs
weight: 80
url: /es/aspose.slides.animation/effect/sound/
---

## Propiedad Effect.Sound

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
        
        // Extrae el sonido del efecto en un arreglo de bytes
        byte[] audio = effect.Sound.BinaryData;
    }
}
```

### Véase También

* interfaz [IAudio](../../../aspose.slides/iaudio)
* clase [Effect](../../effect)
* espacio de nombres [Aspose.Slides.Animation](../../effect)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd for Aspose.Slides.dll -->