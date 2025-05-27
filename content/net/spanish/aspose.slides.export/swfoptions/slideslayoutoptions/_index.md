---
title: SlidesLayoutOptions
second_title: Aspose.Slides para referencia de API .NET
description: Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación ISlidesLayoutOptionsaspose.slides/islideslayoutoptions. Esta propiedad no admite la asignación de objetos del tipo HandoutLayoutingOptionsaspose.slides/handoutlayoutingoptions
type: docs
weight: 150
url: /es/aspose.slides.export/swfoptions/slideslayoutoptions/
---

## Propiedad SwfOptions.SlidesLayoutOptions

Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [`ISlidesLayoutOptions`](../../islideslayoutoptions). Esta propiedad no admite la asignación de objetos del tipo [`HandoutLayoutingOptions`](../../handoutlayoutingoptions)

```csharp
public ISlidesLayoutOptions SlidesLayoutOptions { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    SwfOptions options = new SwfOptions
    {
        SlidesLayoutOptions = new NotesCommentsLayoutingOptions
        {
            CommentsPosition = CommentsPositions.Right
        }
    };
    
    pres.Save("pres.swf", SaveFormat.Swf, options);
}
```

### Véase También

* interfaz [ISlidesLayoutOptions](../../islideslayoutoptions)
* clase [SwfOptions](../../swfoptions)
* espacio de nombres [Aspose.Slides.Export](../../swfoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->