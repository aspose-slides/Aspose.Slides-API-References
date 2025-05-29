---
title: DefaultDelay
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene o establece el tiempo de retraso predeterminado en ms.
type: docs
weight: 20
url: /es/aspose.slides.export/presentationanimationsgenerator/defaultdelay/
---

## Propiedad PresentationAnimationsGenerator.DefaultDelay

Obtiene o establece el tiempo de retraso predeterminado [ms].

```csharp
public int DefaultDelay { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("animated.pptx"))
{
    using (var animationsGenerator = new PresentationAnimationsGenerator(presentation.SlideSize.Size.ToSize()))
    {
        animationsGenerator.DefaultDelay = 1000; // 1s
        // ...
        animationsGenerator.Run(presentation.Slides);
    }
}
```

### Ver también

* clase [PresentationAnimationsGenerator](../../presentationanimationsgenerator)
* espacio de nombres [Aspose.Slides.Export](../../presentationanimationsgenerator)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->