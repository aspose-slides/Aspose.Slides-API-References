---
title: AnimateTextType
second_title: Referencia de la API Aspose.Slides para .NET
description: Define un tipo de texto animado para el efecto. El texto de la forma se puede animar por letra, por palabra o todo a la vez. Leer/escribir AnimateTextTypeaspose.slides.animation/ieffect/animatetexttype.
type: docs
weight: 30
url: /es/aspose.slides.animation/ieffect/animatetexttype/
---

## Propiedad IEffect.AnimateTextType

Define un tipo de texto animado para el efecto. El texto de la forma se puede animar por letra, por palabra o todo a la vez. Leer/escribir `AnimateTextType`.

```csharp
public AnimateTextType AnimateTextType { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Obtener el primer efecto de la primera diapositiva.
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];
    
    // Cambiar el tipo de texto animado del efecto a "Por letra"
    firstSlideEffect.AnimateTextType = AnimateTextType.ByLetter;
}
```

### Véase También

* enum [AnimateTextType](../../animatetexttype)
* interface [IEffect](../../ieffect)
* namespace [Aspose.Slides.Animation](../../ieffect)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->