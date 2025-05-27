---
title: SlidesLayoutOptions
second_title: Aspose.Slides para .NET Referencia de API
description: Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions.
type: docs
weight: 100
url: /es/aspose.slides.export/tiffoptions/slideslayoutoptions/
---

## Propiedad TiffOptions.SlidesLayoutOptions

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
    TiffOptions options = new TiffOptions
    {
        SlidesLayoutOptions = new HandoutLayoutingOptions
        {
            Handout = HandoutType.Handouts4Horizontal
        }
    };
    
    pres.Save("pres.tiff", SaveFormat.Tiff, options);
}
```

### Ver También

* interface [ISlidesLayoutOptions](../../islideslayoutoptions)
* class [TiffOptions](../../tiffoptions)
* namespace [Aspose.Slides.Export](../../tiffoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->