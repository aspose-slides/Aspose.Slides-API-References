---
title: ExportHiddenSlides
second_title: Referencia de la API de Aspose.Slides para .NET
description: Determina si las diapositivas ocultas se exportarán.
type: docs
weight: 20
url: /es/aspose.slides.export.xaml/xamloptions/exporthiddenslides/
---

## Propiedad XamlOptions.ExportHiddenSlides

Determina si las diapositivas ocultas se exportarán.

```csharp
public bool ExportHiddenSlides { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save(new XamlOptions { ExportHiddenSlides = true });
}
```

### Véase También

* clase [XamlOptions](../../xamloptions)
* espacio de nombres [Aspose.Slides.Export.Xaml](../../xamloptions)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->