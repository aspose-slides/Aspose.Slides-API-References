---
title: SlidesLayoutOptions
second_title: Aspose.Sildes para .NET API Reference
description: Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions.
type: docs
weight: 100
url: /es/aspose.slides.export/htmloptions/slideslayoutoptions/
---

## HtmlOptions.SlidesLayoutOptions property

Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [`ISlidesLayoutOptions`](../../islideslayoutoptions).

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

### Ver También

* interface [ISlidesLayoutOptions](../../islideslayoutoptions)
* class [HtmlOptions](../../htmloptions)
* namespace [Aspose.Slides.Export](../../htmloptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->