---
title: ExportHiddenSlides
second_title: Referencia API de Aspose.Slides para .NET
description: Determina si se exportarán las diapositivas ocultas. El valor predeterminado es falso.
type: docs
weight: 30
url: /es/aspose.slides.export/igifoptions/exporthiddenslides/
---

## Propiedad IGifOptions.ExportHiddenSlides

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

### Vea También

* interfaz [IGifOptions](../../igifoptions)
* espacio de nombres [Aspose.Slides.Export](../../igifoptions)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->