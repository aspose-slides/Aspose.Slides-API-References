---
title: AfterAnimationType
second_title: Referencia de API de Aspose.Slides para .NET
description: Define un tipo de animación posterior para el efecto. Lectura/escritura AfterAnimationTypeaspose.slides.animation/ieffect/afteranimationtype.
type: docs
weight: 20
url: /es/aspose.slides.animation/ieffect/afteranimationtype/
---

## Propiedad IEffect.AfterAnimationType

Define un tipo de animación posterior para el efecto. Lectura/escritura `AfterAnimationType`.

```csharp
public AfterAnimationType AfterAnimationType { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Obtener el primer efecto de la primera diapositiva.
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];
    
    // Cambiar la animación posterior del efecto a "Ocultar en el siguiente clic de ratón"
    firstSlideEffect.AfterAnimationType = AfterAnimationType.HideOnNextMouseClick;
}
```

### Véase también

* enum [AfterAnimationType](../../afteranimationtype)
* interface [IEffect](../../ieffect)
* namespace [Aspose.Slides.Animation](../../ieffect)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->