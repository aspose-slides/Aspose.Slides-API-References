---
title: TargetSection
second_title: Aspose.Sildes para la referencia de la API de .NET
description: Obtiene o establece el objeto sección al que se vincula el objeto de Zoom de Sección. Lectura/escritura ISectionaspose.slides/isection.
type: docs
weight: 10
url: /es/aspose.slides/sectionzoomframe/targetsection/
---

## Propiedad SectionZoomFrame.TargetSection

Obtiene o establece el objeto sección al que se vincula el objeto de Zoom de Sección. Lectura/escritura [`ISection`](../../isection).

```csharp
public ISection TargetSection { get; set; }
```

### Ejemplos

El siguiente ejemplo demuestra el cambio de la sección objetivo y crea una nueva imagen para el objeto de zoom de sección:

```csharp
[C#]
using (Presentation pres = new Presentation())
{
  ISectionZoomFrame sectionZoomFrame = pres.Slides[0].Shapes.AddSectionZoomFrame(150, 20, 50, 50, pres.Sections[1]);
  sectionZoomFrame.TargetSection = pres.Sections[2];
}
```

### Ver También

* interfaz [ISection](../../isection)
* clase [SectionZoomFrame](../../sectionzoomframe)
* espacio de nombres [Aspose.Slides](../../sectionzoomframe)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->