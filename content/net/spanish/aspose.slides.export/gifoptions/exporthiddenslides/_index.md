---
title: ExportHiddenSlides
second_title: Referencia de API de Aspose.Slides para .NET
description: Determina si las diapositivas ocultas se exportarán. El valor por defecto es falso.
type: docs
weight: 30
url: /es/aspose.slides.export/gifoptions/exporthiddenslides/
---

## Propiedad GifOptions.ExportHiddenSlides

Determina si las diapositivas ocultas se exportarán. El valor por defecto es falso.

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

### Véase También

* clase [GifOptions](../../gifoptions)
* espacio de nombres [Aspose.Slides.Export](../../gifoptions)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->