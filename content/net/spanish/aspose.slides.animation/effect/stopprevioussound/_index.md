---
title: StopPreviousSound
second_title: Referencia de la API de Aspose.Slides para .NET
description: Este atributo especifica si el efecto de animación detiene el sonido anterior. Booleano de lectura/escritura.
type: docs
weight: 90
url: /es/aspose.slides.animation/effect/stopprevioussound/
---

## Propiedad Effect.StopPreviousSound

Este atributo especifica si el efecto de animación detiene el sonido anterior. Booleano de lectura/escritura.

```csharp
public bool StopPreviousSound { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Obtener el primer efecto de la primera diapositiva.
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];
    
    // Obtener el primer efecto de la segunda diapositiva.
    IEffect secondSlideEffect = presentation.Slides[1].Timeline.MainSequence[0];
       
    if (firstSlideEffect.Sound != null)
    {
        // Cambiar el segundo efecto Mejoras/Sonido a "Detener Sonido Anterior"
        secondSlideEffect.StopPreviousSound = true;
    }
}
```

### Véase también

* clase [Effect](../../effect)
* espacio de nombres [Aspose.Slides.Animation](../../effect)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->