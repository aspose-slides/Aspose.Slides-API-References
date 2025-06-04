---
title: TargetSlide
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene o establece el objeto de diapositiva al que se vincula el objeto Slide Zoom. Lectura/escritura ISlideaspose.slides/islide.
type: docs
weight: 10
url: /es/aspose.slides/zoomframe/targetslide/
---

## Propiedad ZoomFrame.TargetSlide

Obtiene o establece el objeto de diapositiva al que se vincula el objeto Slide Zoom. Lectura/escritura [`ISlide`](../../islide).

```csharp
public ISlide TargetSlide { get; set; }
```

### Ejemplos

El siguiente ejemplo demuestra cómo cambiar la diapositiva objetivo y crear una nueva imagen para el objeto Slide Zoom:

```csharp
[C#]
IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
zoomFrame.TargetSlide = pres.Slides[2];
```

### Vea También

* interfaz [ISlide](../../islide)
* clase [ZoomFrame](../../zoomframe)
* espacio de nombres [Aspose.Slides](../../zoomframe)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->