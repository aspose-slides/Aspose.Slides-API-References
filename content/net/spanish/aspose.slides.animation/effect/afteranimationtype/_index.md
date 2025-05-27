---
title: AfterAnimationType
second_title: Referencia de API de Aspose.Slides para .NET
description: Define un tipo de animación posterior para el efecto. Lectura/escritura AfterAnimationTypeaspose.slides.animation/effect/afteranimationtype.
type: docs
weight: 20
url: /es/aspose.slides.animation/effect/afteranimationtype/
---

## Propiedad Effect.AfterAnimationType

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
    
    // Cambiar el efecto de animación posterior a "Ocultar en el siguiente clic del mouse"
    firstSlideEffect.AfterAnimationType = AfterAnimationType.HideOnNextClick;
}
```

### Vea También

* enum [AfterAnimationType](../../afteranimationtype)
* class [Effect](../../effect)
* namespace [Aspose.Slides.Animation](../../effect)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->