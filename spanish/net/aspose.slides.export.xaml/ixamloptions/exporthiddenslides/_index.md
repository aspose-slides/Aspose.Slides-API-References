---
title: ExportHiddenSlides
second_title: Referencia de la API de Aspose.Slides para .NET
description: Determina si se exportarán las diapositivas ocultas.
type: docs
weight: 20
url: /es/net/aspose.slides.export.xaml/ixamloptions/exporthiddenslides/
---
## IXamlOptions.ExportHiddenSlides property

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

### Ver también

* interface [IXamlOptions](../../ixamloptions)
* espacio de nombres [Aspose.Slides.Export.Xaml](../../ixamloptions)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->