---
title: CaptionTracks
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve la colección de subtítulos cerrados del video. Solo lectura ICaptionsCollectionaspose.slides/icaptionscollection.
type: docs
weight: 20
url: /es/aspose.slides/ivideoframe/captiontracks/
---

## Propiedad IVideoFrame.CaptionTracks

Devuelve la colección de subtítulos cerrados del video. Solo lectura [`ICaptionsCollection`](../../icaptionscollection).

```csharp
public ICaptionsCollection CaptionTracks { get; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("video with captions.pptx"))
{
    foreach (IShape shape in pres.Slides[0].Shapes)
    {
        if (!(shape is IVideoFrame videoFrame)) continue;

        foreach (var captionTrack in videoFrame.CaptionTracks)
        {
            // Extrae los datos binarios de los subtítulos y los guarda en el archivo
            System.IO.File.WriteAllBytes(captionTrack.CaptionId + ".vtt", captionTrack.BinaryData);
        }
    }
}
```

### Ver También

* interfaz [ICaptionsCollection](../../icaptionscollection)
* interfaz [IVideoFrame](../../ivideoframe)
* espacio de nombres [Aspose.Slides](../../ivideoframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->