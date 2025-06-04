---
title: AdvanceAfter
second_title: Referencia de API de Aspose.Slides para .NET
description: Este atributo especifica si la presentación de diapositivas se moverá a la siguiente diapositiva después de un cierto tiempo. Booleano de lectura/escritura.
type: docs
weight: 10
url: /es/aspose.slides/islideshowtransition/advanceafter/
---

## ISlideShowTransition.AdvanceAfter property

Este atributo especifica si la presentación de diapositivas se moverá a la siguiente diapositiva después de un cierto tiempo. Booleano de lectura/escritura.

```csharp
public bool AdvanceAfter { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
    // Obtener la primera Transición de diapositiva
    ISlideShowTransition slideTransition = pres.Slides[0].SlideShowTransition;
    
    // Verificar si la bandera de Avance de Diapositiva Después está marcada
    if (slideTransition.AdvanceAfter)
    {
        // Obtener el valor del tiempo de Avance de Diapositiva Después
        uint advanceAfterTime = slideTransition.AdvanceAfterTime;
    }
}
```

### Ver También

* interfaz [ISlideShowTransition](../../islideshowtransition)
* namespace [Aspose.Slides](../../islideshowtransition)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->