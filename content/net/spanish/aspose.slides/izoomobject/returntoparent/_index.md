---
title: ReturnToParent
second_title: Referencia de la API Aspose.Slides para .NET
description: Obtiene o establece el comportamiento de navegación en la presentación de diapositivas. Booleano de lectura/escritura. Valor predeterminado falso
type: docs
weight: 30
url: /es/aspose.slides/izoomobject/returntoparent/
---

## Propiedad IZoomObject.ReturnToParent

Obtiene o establece el comportamiento de navegación en la presentación de diapositivas. Booleano de lectura/escritura. Valor predeterminado: falso

```csharp
public bool ReturnToParent { get; set; }
```

### Observaciones

El valor verdadero de la propiedad especifica el comportamiento de navegación de retorno al padre en la presentación de diapositivas.

### Ejemplos

Ejemplo:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IZoomFrame zoomFrame = pres.Slides[0].Shapes.AddZoomFrame(150, 20, 50, 50, pres.Slides[1]);
    zoomFrame.ReturnToParent = true;
}
```

### Véase también

* interfaz [IZoomObject](../../izoomobject)
* espacio de nombres [Aspose.Slides](../../izoomobject)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->