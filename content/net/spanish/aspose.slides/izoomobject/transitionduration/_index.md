---
title: TransitionDuration
second_title: Aspose.Slides para .NET API Reference
description: Obtiene o establece la duración de la transición entre Zoom y diapositiva. Lectura/escritura Single. Valor predeterminado 1.0f
type: docs
weight: 50
url: /es/aspose.slides/izoomobject/transitionduration/
---

## Propiedad IZoomObject.TransitionDuration

Obtiene o establece la duración de la transición entre Zoom y diapositiva. Lectura/escritura Single. Valor predeterminado: 1.0f

```csharp
public float TransitionDuration { get; set; }
```

### Comentarios

Si no se especifica (TransitionDur = 0), utilizará la transición de la diapositiva de destino y los tiempos asociados con esa transición.

### Ejemplos

el ejemplo demuestra cómo cambiar la duración de la transición entre Zoom y diapositiva:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
    zoomFrame.TransitionDuration = 2.5f;
}
```

### Véase también

* interfaz [IZoomObject](../../izoomobject)
* espacio de nombres [Aspose.Slides](../../izoomobject)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->