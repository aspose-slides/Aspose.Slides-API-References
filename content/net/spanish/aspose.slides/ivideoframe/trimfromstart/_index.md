---
title: TrimFromStart
second_title: Aspose.Slides para .NET Referencia de API
description: Recortar inicio ms
type: docs
weight: 110
url: /es/aspose.slides/ivideoframe/trimfromstart/
---

## Propiedad IVideoFrame.TrimFromStart

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

    //establecer el tiempo de inicio de recorte 1seg
    videoFrame.TrimFromStart = 1000f;

    //establecer el tiempo de finalización de recorte 2seg
    videoFrame.TrimFromEnd = 2000f;
}
```

### Ver También

* interfaz [IVideoFrame](../../ivideoframe)
* espacio de nombres [Aspose.Slides](../../ivideoframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->