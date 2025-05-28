---
title: DelayBetweenTextParts
second_title: Referencia de API de Aspose.Slides para .NET
description: Define un retraso entre partes de texto animadas palabras o letras. Un valor positivo especifica el porcentaje de la duración del efecto. Un valor negativo especifica el retraso en segundos. Lectura/escritura Single.
type: docs
weight: 50
url: /es/aspose.slides.animation/ieffect/delaybetweentextparts/
---

## Propiedad IEffect.DelayBetweenTextParts

Define un retraso entre partes de texto animadas (palabras o letras). Un valor positivo especifica el porcentaje de la duración del efecto. Un valor negativo especifica el retraso en segundos. Lectura/escritura Single.

```csharp
public float DelayBetweenTextParts { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    // Obtener el primer efecto de la primera diapositiva.
    IEffect firstSlideEffect = presentation.Slides[0].Timeline.MainSequence[0];
    
    // Cambiar el tipo de animación de texto del efecto a "Por palabra"
    firstSlideEffect.AnimateTextType = AnimateTextType.ByWord;
    
    // Establecer el retraso entre partes de texto animadas al 20% de la duración del efecto.
    firstSlideEffect.DelayBetweenTextParts = 20f;
}
```

### Vea También

* interfaz [IEffect](../../ieffect)
* espacio de nombres [Aspose.Slides.Animation](../../ieffect)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->