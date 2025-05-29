---
title: RepeatUntilEndSlide
second_title: Aspose.Slides para .NET Referencia de la API
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
    // Obtener la secuencia de efectos para la primera diapositiva
    ISequence effectsSequence = presentation.Slides[0].Timeline.MainSequence;

    // Obtener el primer efecto de la secuencia principal.
    IEffect effect = effectsSequence[0];

    // Cambiar el Timing/Repeat del efecto a "Hasta el final de la diapositiva"
    effect.Timing.RepeatUntilEndSlide = true;
}
```

### Véase También

* clase [Timing](../../timing)
* espacio de nombres [Aspose.Slides.Animation](../../timing)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->