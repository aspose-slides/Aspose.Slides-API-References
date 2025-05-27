---
title: SlidesLayoutOptions
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene o establece el modo en el que se colocan las diapositivas en la página al exportar una presentación ISlidesLayoutOptionsaspose.slides.export/islideslayoutoptions. Esta propiedad no admite la asignación de objetos de tipo Aspose.Slides.Export.HandoutLayoutingOptions
type: docs
weight: 150
url: /es/aspose.slides.export/iswfoptions/slideslayoutoptions/
---

## Propiedad ISwfOptions.SlidesLayoutOptions

Obtiene o establece el modo en el que se colocan las diapositivas en la página al exportar una presentación [`ISlidesLayoutOptions`](../../islideslayoutoptions). Esta propiedad no admite la asignación de objetos de tipo `Aspose.Slides.Export.HandoutLayoutingOptions`

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

### Vea También

* interfaz [ISlidesLayoutOptions](../../islideslayoutoptions)
* interfaz [ISwfOptions](../../iswfoptions)
* espacio de nombres [Aspose.Slides.Export](../../iswfoptions)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->