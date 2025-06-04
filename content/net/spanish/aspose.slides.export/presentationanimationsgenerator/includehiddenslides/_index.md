---
title: IncludeHiddenSlides
second_title: Referencia de la API Aspose.Sildes para .NET
description: Obtiene o establece si las diapositivas ocultas deben ser incluidas.
type: docs
weight: 40
url: /es/aspose.slides.export/presentationanimationsgenerator/includehiddenslides/
---

## Propiedad PresentationAnimationsGenerator.IncludeHiddenSlides

Obtiene o establece si las diapositivas ocultas deben ser incluidas.

```csharp
public bool IncludeHiddenSlides { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation presentation = new Presentation("animated.pptx"))
{
    using (var animationsGenerator = new PresentationAnimationsGenerator(presentation.SlideSize.Size.ToSize()))
    {
        animationsGenerator.IncludeHiddenSlides = false;
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