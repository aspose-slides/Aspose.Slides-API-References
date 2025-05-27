---
title: TargetSection
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene o establece el objeto de sección al que está vinculado el objeto de Zoom de Sección. Lectura/escritura ISectionaspose.slides/isection.
type: docs
weight: 20
url: /es/aspose.slides/isectionzoomframe/targetsection/
---

## Propiedad ISectionZoomFrame.TargetSection

Obtiene o establece el objeto de sección al que está vinculado el objeto de Zoom de Sección. Lectura/escritura [`ISection`](../../isection).

```csharp
public ISection TargetSection { get; set; }
```

### Ejemplos

Este ejemplo demuestra cómo cambiar la sección objetivo y crea una nueva imagen para el objeto de zoom de sección:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
  ISectionZoomFrame sectionZoomFrame = pres.Slides[0].Shapes.AddSectionZoomFrame(150, 20, 50, 50, pres.Sections[1]);
  sectionZoomFrame.TargetSection = pres.Sections[2];
}
```

### Véase También

* interfaz [ISection](../../isection)
* interfaz [ISectionZoomFrame](../../isectionzoomframe)
* espacio de nombres [Aspose.Slides](../../isectionzoomframe)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->