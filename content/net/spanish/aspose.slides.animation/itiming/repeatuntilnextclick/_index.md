---
title: RepeatUntilNextClick
second_title: Aspose.Slides para .NET Referencia de API
description: Este atributo especifica si el efecto se repetirá hasta el siguiente clic. Booleano de lectura/escritura.
type: docs
weight: 80
url: /es/aspose.slides.animation/itiming/repeatuntilnextclick/
---

## Propiedad ITiming.RepeatUntilNextClick

Este atributo especifica si el efecto se repetirá hasta el siguiente clic. Booleano de lectura/escritura.

```csharp
public bool RepeatUntilNextClick { get; set; }
```

### Ejemplos

```csharp
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Obtener la secuencia de efectos para la primera diapositiva
    ISequence effectsSequence = presentation.Slides[0].Timeline.MainSequence;

    // Obtener el primer efecto de la secuencia principal.
    IEffect effect = effectsSequence[0];

    // Cambiar el tiempo del efecto/Repetir a "Hasta el siguiente clic"
    effect.Timing.RepeatUntilNextClick = true;
}
```

### Véase también

* interfaz [ITiming](../../itiming)
* namespace [Aspose.Slides.Animation](../../itiming)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->