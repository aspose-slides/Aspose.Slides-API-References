---
title: ExportHiddenSlides
second_title: Referencia de la API de Aspose.Slides para .NET
description: Determina si se exportarán las diapositivas ocultas. El valor predeterminado es falso.
type: docs
weight: 30
url: /es/net/aspose.slides.export/gifoptions/exporthiddenslides/
---
## GifOptions.ExportHiddenSlides property

Determina si se exportarán las diapositivas ocultas. El valor predeterminado es falso.

```csharp
public bool ExportHiddenSlides { get; set; }
```

### Ejemplos

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
	pres.Save("pres.gif", SaveFormat.Gif, new GifOptions { ExportHiddenSlides = false });
}
```

### Ver también

* class [GifOptions](../../gifoptions)
* espacio de nombres [Aspose.Slides.Export](../../gifoptions)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->