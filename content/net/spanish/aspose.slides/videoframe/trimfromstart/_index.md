---
title: TrimFromStart
second_title: Referencia de API de Aspose.Sildes para .NET
description: Recortar inicio ms
type: docs
weight: 100
url: /es/aspose.slides/videoframe/trimfromstart/
---

## Propiedad VideoFrame.TrimFromStart

Recortar inicio [ms]

```csharp
public float TrimFromStart { get; set; }
```

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    ISlide slide = pres.Slides[0];
    IVideo video = pres.Videos.AddVideo(File.ReadAllBytes("video.mp4"));
    var videoFrame = slide.Shapes.AddVideoFrame(0, 0, 100, 100, video);

    //establecer tiempo de inicio de recorte 1seg
    videoFrame.TrimFromStart = 1000f;

    //establecer tiempo de finalización de recorte 2seg
    videoFrame.TrimFromEnd = 2000f;
}
```

### Véase también

* clase [VideoFrame](../../videoframe)
* espacio de nombres [Aspose.Slides](../../videoframe)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->