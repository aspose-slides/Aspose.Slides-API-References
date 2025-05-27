---
title: DisableFontLigatures
second_title: Aspose.Slides para .NET API Reference
description: Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en verdadero, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad se establece en falso.
type: docs
weight: 20
url: /es/aspose.slides.export/renderingoptions/disablefontligatures/
---

## Propiedad RenderingOptions.DisableFontLigatures

Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en `true`, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad se establece en `false`.

```csharp
public bool DisableFontLigatures { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    RenderingOptions options = new RenderingOptions
    {
        DisableFontLigatures = true // Desactivar ligaduras en la renderización de texto
    };
    
    Bitmap[] renderedSlides = pres.GetImage(options);
    for (var index = 0; index < renderedSlides.Length; index++)
    {
        var slideImage = renderedSlides[index];
        slideImage.Save($"slide-{index}.png");
    }
}
```

### Ver También

* clase [RenderingOptions](../../renderingoptions)
* espacio de nombres [Aspose.Slides.Export](../../renderingoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->