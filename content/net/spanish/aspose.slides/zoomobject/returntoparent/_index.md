---
title: ReturnToParent
second_title: Aspose.Slides para la referencia de la API de .NET
description: Obtiene o establece el comportamiento de navegación en la presentación de diapositivas. Lectura/escritura Booleano. Valor predeterminado falso
type: docs
weight: 20
url: /es/aspose.slides/zoomobject/returntoparent/
---

## ZoomObject.ReturnToParent propiedad

Obtiene o establece el comportamiento de navegación en la presentación de diapositivas. Lectura/escritura Booleano. Valor predeterminado: falso

```csharp
public bool ReturnToParent { get; set; }
```

### Comentarios

El valor verdadero de la propiedad especifica el comportamiento de navegación de regreso al padre en la presentación de diapositivas.

### Ejemplos

Ejemplo:

```csharp
[C#]
IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
zoomFrame.ReturnToParent = true;
```

### Véase también

* clase [ZoomObject](../../zoomobject)
* espacio de nombres [Aspose.Slides](../../zoomobject)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->
