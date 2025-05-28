---
title: AfterAnimationColor
second_title: Referencia de API de Aspose.Slides para .NET
description: Define un color después de la animación para el efecto. Lectura/escritura IColorFormataspose.slides/icolorformat.
type: docs
weight: 10
url: /es/aspose.slides.animation/ieffect/afteranimationcolor/
---

## Propiedad IEffect.AfterAnimationColor

Define un color después de la animación para el efecto. Lectura/escritura [`IColorFormat`](../../../aspose.slides/icolorformat).

```csharp
public IColorFormat AfterAnimationColor { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Obtener el primer efecto de la primera diapositiva.
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];
    
    // Cambiar el tipo de animación después del efecto a "Color"
    firstSlideEffect.AfterAnimationType = AfterAnimationType.Color;
    
    // Establecer el color después de la animación del efecto.
    firstSlideEffect.AfterAnimationColor.Color = Color.Green;
}
```

### Ver También

* interfaz [IColorFormat](../../../aspose.slides/icolorformat)
* interfaz [IEffect](../../ieffect)
* espacio de nombres [Aspose.Slides.Animation](../../ieffect)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->