---
title: ShowBackground
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene o establece el valor que especifica si Zoom utilizará el fondo de la diapositiva de destino. Lectura/escrituraBoolean. Valor por defecto true
type: docs
weight: 50
url: /es/net/aspose.slides/izoomobject/showbackground/
---
## IZoomObject.ShowBackground property

Obtiene o establece el valor que especifica si Zoom utilizará el fondo de la diapositiva de destino. Lectura/escrituraBoolean. Valor por defecto: true

```csharp
public bool ShowBackground { get; set; }
```

### Ejemplos

El ejemplo demuestra cómo eliminar el fondo de una imagen de un objeto Zoom:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
    zoomFrame.ShowBackground = false;
}
```

### Ver también

* interface [IZoomObject](../../izoomobject)
* espacio de nombres [Aspose.Slides](../../izoomobject)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->