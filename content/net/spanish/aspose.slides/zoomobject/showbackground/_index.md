---
title: ShowBackground
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene o establece el valor que especifica si el Zoom utilizará el fondo de la diapositiva de destino. Booleano de lectura/escritura. Valor predeterminado verdadero
type: docs
weight: 30
url: /es/aspose.slides/zoomobject/showbackground/
---

## Propiedad ZoomObject.ShowBackground

Obtiene o establece el valor que especifica si el Zoom utilizará el fondo de la diapositiva de destino. Booleano de lectura/escritura. Valor predeterminado: verdadero

```csharp
public bool ShowBackground { get; set; }
```

### Ejemplos

El ejemplo demuestra cómo quitar el fondo de una imagen de un objeto Zoom:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
    zoomFrame.ShowBackground = false;
}
```

### Véase También

* clase [ZoomObject](../../zoomobject)
* espacio de nombres [Aspose.Slides](../../zoomobject)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->