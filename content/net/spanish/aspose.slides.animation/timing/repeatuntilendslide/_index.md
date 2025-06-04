---
title: RepeatUntilEndSlide
second_title: Aspose.Slides for .NET API Reference
description: Este atributo especifica si el efecto se repetirá hasta el final de la diapositiva. Booleano de lectura/escritura.
type: docs
weight: 70
url: /es/aspose.slides.animation/timing/repeatuntilendslide/
---

## Propiedad Timing.RepeatUntilEndSlide

Este atributo especifica si el efecto se repetirá hasta el final de la diapositiva. Booleano de lectura/escritura.

```csharp
public bool RepeatUntilEndSlide { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Obtén la secuencia de efectos para la primera diapositiva
    ISequence effectsSequence = presentation.Slides[0].Timeline.MainSequence;

    // Obtén el primer efecto de la secuencia principal.
    IEffect effect = effectsSequence[0];

    // Cambia el Timing/Repeat del efecto a "Hasta el final de la diapositiva"
    effect.Timing.RepeatUntilEndSlide = true;
}
```

### Ver También

* class [Timing](../../timing)
* namespace [Aspose.Slides.Animation](../../timing)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITES: generado por xmldocmd para Aspose.Slides.dll -->