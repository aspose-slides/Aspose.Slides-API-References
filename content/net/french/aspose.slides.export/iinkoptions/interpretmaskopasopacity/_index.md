---
title: InterpretMaskOpAsOpacity
second_title: Référence de l'API Aspose.Slides pour .NET
description: Utilise l'opération ROP ou l'opacité pour le rendu du pinceau.
type: docs
weight: 20
url: /fr/aspose.slides.export/iinkoptions/interpretmaskopasopacity/
---

## IInkOptions.InterpretMaskOpAsOpacity propriété

Utilise l'opération ROP ou l'opacité pour le rendu du pinceau.

```csharp
public bool InterpretMaskOpAsOpacity { get; set; }
```

### Remarques

La valeur par défaut est vraie.

### Exemples

L'exemple suivant démontre comment utiliser ROP pour exporter des éléments Ink:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    PdfOptions pdfOptions = new PdfOptions();
    pdfOptions.InkOptions.InterpretMaskOpAsOpacity = false;
    pres.Save("output.pptx", SaveFormat.Pdf, pdfOptions);
}
```

### Voir aussi

* interface [IInkOptions](../../iinkoptions)
* namespace [Aspose.Slides.Export](../../iinkoptions)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->