---
title: Rewind
second_title: Referencia de la API de Aspose.Slides para .NET
description: Este atributo especifica si el efecto se retrocederá al terminar de reproducirse. Booleano de lectura/escritura.
type: docs
weight: 100
url: /es/aspose.slides.animation/itiming/rewind/
---

## Propiedad ITiming.Rewind

Este atributo especifica si el efecto se retrocederá al terminar de reproducirse. Booleano de lectura/escritura.

```csharp
public bool Rewind { get; set; }
```

### Ejemplos

```csharp
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Obtener la secuencia de efectos para la primera diapositiva
    ISequence effectsSequence = presentation.Slides[0].Timeline.MainSequence;

    // Obtener el primer efecto de la secuencia principal.
    IEffect effect = effectsSequence[0];

    // Activar el Rewind del efecto Timing.
    effect.Timing.Rewind = true;
}
```

### Ver También

* interfaz [ITiming](../../itiming)
* espacio de nombres [Aspose.Slides.Animation](../../itiming)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->