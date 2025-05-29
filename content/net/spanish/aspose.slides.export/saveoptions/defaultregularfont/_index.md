---
title: DefaultRegularFont
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente de origen. Cadena de lectura/escritura.
type: docs
weight: 10
url: /es/aspose.slides.export/saveoptions/defaultregularfont/
---

## Propiedad SaveOptions.DefaultRegularFont

Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente de origen. Cadena de lectura/escritura.

```csharp
public string DefaultRegularFont { get; set; }
```

### Ejemplos

```csharp
[C#]

using (Presentation pres = new Presentation("SomePresentation.pptx"))
{
	HtmlOptions htmlOpts = new HtmlOptions();
	htmlOpts.DefaultRegularFont = "Arial Black";
	pres.Save(@"SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
	htmlOpts.DefaultRegularFont = "Lucida Console";
	pres.Save(@"Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);

	PdfOptions pdfOpts = new PdfOptions();
	pdfOpts.DefaultRegularFont = "Arial Black";
	pres.Save(@"SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
}
```

### Ver También

* clase [SaveOptions](../../saveoptions)
* espacio de nombres [Aspose.Slides.Export](../../saveoptions)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->