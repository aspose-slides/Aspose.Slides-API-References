---
title: OpcionesDeDiseñoDeDiapositivas
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions.
type: docs
weight: 180
url: /es/aspose.slides.export/pdfoptions/slideslayoutoptions/
---

## Propiedad PdfOptions.SlidesLayoutOptions

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
    PdfOptions options = new PdfOptions
    {
        SlidesLayoutOptions = new HandoutLayoutingOptions
        {
            Handout = HandoutType.Handouts4Horizontal
        }
    };
    
    pres.Save("pres.pdf", SaveFormat.Pdf, options);
}
```

### Ver También

* interfaz [ISlidesLayoutOptions](../../islideslayoutoptions)
* clase [PdfOptions](../../pdfoptions)
* espacio de nombres [Aspose.Slides.Export](../../pdfoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->