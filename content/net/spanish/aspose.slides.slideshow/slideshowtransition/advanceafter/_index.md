---
title: AdvanceAfter
second_title: Aspose.Sildes para .NET Referencia de API
description: Este atributo especifica si la presentación pasará a la siguiente diapositiva después de un cierto tiempo. Booleano de lectura/escritura.
type: docs
weight: 10
url: /es/aspose.slides.slideshow/slideshowtransition/advanceafter/
---

## SlideShowTransition.AdvanceAfter property

Este atributo especifica si la presentación pasará a la siguiente diapositiva después de un cierto tiempo. Booleano de lectura/escritura.

```csharp
public bool AdvanceAfter { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("demo.pptx"))
{
    // Obtener la transición de la primera diapositiva
    ISlideShowTransition slideTransition = pres.Slides[0].SlideShowTransition;
    
    // Verificar si la opción Avanzar Diapositiva Después está marcada
    if (slideTransition.AdvanceAfter)
    {
        // Obtener el valor de tiempo para Avanzar Diapositiva Después
        uint advanceAfterTime = slideTransition.AdvanceAfterTime;
    }
}
```

### Ver también

* class [SlideShowTransition](../../slideshowtransition)
* namespace [Aspose.Slides.SlideShow](../../slideshowtransition)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->