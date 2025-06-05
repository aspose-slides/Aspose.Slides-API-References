---
title: PrintComments
second_title: Referencia de API de Aspose.Slides para .NET
description: Especifica si se deben mostrar o no los comentarios en las diapositivas
type: docs
weight: 30
url: /es/aspose.slides.export/handoutlayoutingoptions/printcomments/
---

## Propiedad HandoutLayoutingOptions.PrintComments

Especifica si se deben mostrar o no los comentarios en las diapositivas

```csharp
public bool PrintComments { get; set; }
```

### Observaciones

El valor predeterminado es **false**.

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
            PrintComments = false
        }
    };
    
    pres.Slides[0].GetThumbnail(options, new Size(1920, 1080)).Save("pres-handout.png");
}
```

### Véase También

* clase [HandoutLayoutingOptions](../../handoutlayoutingoptions)
* espacio de nombres [Aspose.Slides.Export](../../handoutlayoutingoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->