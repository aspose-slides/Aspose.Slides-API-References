---
title: Handout
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica cuántas diapositivas y en qué secuencia se colocarán en la página HandoutTypeaspose.slides.export/handouttype.
type: docs
weight: 20
url: /es/aspose.slides.export/handoutlayoutingoptions/handout/
---

## Propiedad Handout de HandoutLayoutingOptions

Especifica cuántas diapositivas y en qué secuencia se colocarán en la página [`HandoutType`](../../handouttype).

```csharp
public HandoutType Handout { get; set; }
```

### Notas

El valor predeterminado es **HandoutType.Handouts6Horizontal**.

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
            Handout = HandoutType.Handouts4Horizontal
        }
    };
    
    pres.Slides[0].GetThumbnail(options, new Size(1920, 1080)).Save("pres-handout.png");
}
```

### Véase También

* enum [HandoutType](../../handouttype)
* class [HandoutLayoutingOptions](../../handoutlayoutingoptions)
* namespace [Aspose.Slides.Export](../../handoutlayoutingoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->