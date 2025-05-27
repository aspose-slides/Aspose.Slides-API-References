---
title: ExportHiddenSlides
second_title: Referencia de la API de Aspose.Slides para .NET
description: Determina si se exportarán las diapositivas ocultas.
type: docs
weight: 20
url: /es/aspose.slides.export.xaml/ixamloptions/exporthiddenslides/
---

## Propiedad IXamlOptions.ExportHiddenSlides

Determina si se exportarán las diapositivas ocultas.

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

### Véase también

* interfaz [IXamlOptions](../../ixamloptions)
* espacio de nombres [Aspose.Slides.Export.Xaml](../../ixamloptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->