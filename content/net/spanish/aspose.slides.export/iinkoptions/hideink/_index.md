---
title: HideInk
second_title: Referencia de API de Aspose.Slides para .NET
description: Muestra u oculta elementos de Ink en el documento exportado.
type: docs
weight: 10
url: /es/aspose.slides.export/iinkoptions/hideink/
---

## IInkOptions.HideInk propiedad

Muestra u oculta elementos de Ink en el documento exportado.

```csharp
public bool HideInk { get; set; }
```

### Observaciones

El valor predeterminado es falso.

### Ejemplos

El siguiente ejemplo demuestra cómo ocultar elementos de Ink en un documento PDF exportado:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    PdfOptions pdfOptions = new PdfOptions();
    pdfOptions.InkOptions.HideInk = true;
    pres.Save("output.pptx", SaveFormat.Pdf, pdfOptions);
}
```

### Véase también

* interfaz [IInkOptions](../../iinkoptions)
* espacio de nombres [Aspose.Slides.Export](../../iinkoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->