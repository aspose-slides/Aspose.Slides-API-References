---
title: SlidesLayoutOptions
second_title: Aspose.Sildes para .NET Referencia de la API
description: Obtiene o establece el modo en que se colocan las diapositivas en la página al exportar una presentación ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions.
type: docs
weight: 40
url: /es/aspose.slides.export/irenderingoptions/slideslayoutoptions/
---

## IRenderingOptions.SlidesLayoutOptions propiedad

Obtiene o establece el modo en que se colocan las diapositivas en la página al exportar una presentación [`ISlidesLayoutOptions`](../../islideslayoutoptions).

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

### Vea También

* interface [ISlidesLayoutOptions](../../islideslayoutoptions)
* interface [IRenderingOptions](../../irenderingoptions)
* namespace [Aspose.Slides.Export](../../irenderingoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->