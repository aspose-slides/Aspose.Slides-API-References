---
title: SlidesLayoutOptions
second_title: Aspose.Slides para referencia de API .NET
description: Obtiene o establece el modo en el que se colocan las diapositivas en la página al exportar una presentación ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions.
type: docs
weight: 40
url: /es/aspose.slides.export/renderingoptions/slideslayoutoptions/
---

## Propiedad RenderingOptions.SlidesLayoutOptions

Obtiene o establece el modo en el que se colocan las diapositivas en la página al exportar una presentación [`ISlidesLayoutOptions`](../../islideslayoutoptions).

```csharp
public ISlidesLayoutOptions SlidesLayoutOptions { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    RenderingOptions options = new RenderingOptions
    {
        SlidesLayoutOptions = new HandoutLayoutingOptions
        {
            Handout = HandoutType.Handouts4Horizontal,
            PrintSlideNumbers = false
        }
    };
    
    Bitmap[] handoutSlides = pres.GetThumbnails(options);
    for (var index = 0; index < handoutSlides.Length; index++)
    {
        var handoutSllide = handoutSlides[index];
        handoutSllide.Save($"handout-{index}.png");
    }
}
```

### Ver También

* interface [ISlidesLayoutOptions](../../islideslayoutoptions)
* class [RenderingOptions](../../renderingoptions)
* namespace [Aspose.Slides.Export](../../renderingoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->