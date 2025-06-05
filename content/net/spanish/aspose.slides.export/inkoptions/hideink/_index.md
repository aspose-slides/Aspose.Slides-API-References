---
title: HideInk
second_title: Aspose.Slides para .NET Referencia de la API
description: Muestra u oculta elementos de tinta en el documento exportado.
type: docs
weight: 10
url: /es/aspose.slides.export/inkoptions/hideink/
---

## InkOptions.HideInk property

Muestra u oculta elementos de tinta en el documento exportado.

```csharp
public bool HideInk { get; set; }
```

### Observaciones

El valor predeterminado es falso.

### Ejemplos

El siguiente ejemplo demuestra cómo ocultar elementos de tinta en el documento PDF exportado:

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

* class [InkOptions](../../inkoptions)
* namespace [Aspose.Slides.Export](../../inkoptions)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->
