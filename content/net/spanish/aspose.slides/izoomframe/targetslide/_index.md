---
title: TargetSlide
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene o establece el objeto de diapositiva al que se vincula el objeto de Zoom de Diapositiva. Lectura/escritura ISlideaspose.slides/islide.
type: docs
weight: 20
url: /es/aspose.slides/izoomframe/targetslide/
---

## Propiedad IZoomFrame.TargetSlide

Obtiene o establece el objeto de diapositiva al que se vincula el objeto de Zoom de Diapositiva. Lectura/escritura [`ISlide`](../../islide).

```csharp
public ISlide TargetSlide { get; set; }
```

### Ejemplos

El siguiente ejemplo demuestra cómo cambiar la diapositiva objetivo y crear una nueva imagen para el objeto de Zoom de Diapositiva:

```csharp
[C#]
IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
zoomFrame.TargetSlide = pres.Slides[2];
```

### Ver También

* interfaz [ISlide](../../islide)
* interfaz [IZoomFrame](../../izoomframe)
* espacio de nombres [Aspose.Slides](../../izoomframe)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->