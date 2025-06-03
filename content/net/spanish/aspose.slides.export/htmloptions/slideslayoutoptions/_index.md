---
title: SlidesLayoutOptions
second_title: Referencia de la API Aspose.Slides para .NET
description: Obtiene o establece el modo en que se colocan las diapositivas en la página al exportar una presentación ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions.
type: docs
weight: 100
url: /es/aspose.slides.export/htmloptions/slideslayoutoptions/
---

## Propiedad HtmlOptions.SlidesLayoutOptions

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
    HtmlOptions options = new HtmlOptions
    {
        SlidesLayoutOptions = new HandoutLayoutingOptions
        {
            Handout = HandoutType.Handouts4Horizontal,
        }
    };
    
    pres.Save("pres.html", SaveFormat.Html, options);
}
```

### Véase También

* interface [ISlidesLayoutOptions](../../islideslayoutoptions)
* class [HtmlOptions](../../htmloptions)
* namespace [Aspose.Slides.Export](../../htmloptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->