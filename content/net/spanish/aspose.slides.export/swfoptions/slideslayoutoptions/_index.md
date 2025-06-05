---
title: SlidesLayoutOptions
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene o establece el modo en el que se colocan las diapositivas en la página al exportar una presentación ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions. Esta propiedad no admite la asignación de objetos del tipo HandoutLayoutingOptionsaspose.slides.export/handoutlayoutingoptions
type: docs
weight: 150
url: /es/aspose.slides.export/swfoptions/slideslayoutoptions/
---

## Propiedad SwfOptions.SlidesLayoutOptions

Obtiene o establece el modo en el que se colocan las diapositivas en la página al exportar una presentación [`ISlidesLayoutOptions`](../../islideslayoutoptions). Esta propiedad no admite la asignación de objetos del tipo [`HandoutLayoutingOptions`](../../handoutlayoutingoptions)

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

### Véase también

* interfaz [ISlidesLayoutOptions](../../islideslayoutoptions)
* clase [SwfOptions](../../swfoptions)
* namespace [Aspose.Slides.Export](../../swfoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITES: generado por xmldocmd para Aspose.Slides.dll -->