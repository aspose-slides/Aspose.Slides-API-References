---
title: DefaultRegularFont
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente fuente. Lectura-escrituraString .
type: docs
weight: 10
url: /es/net/aspose.slides.export/saveoptions/defaultregularfont/
---
## SaveOptions.DefaultRegularFont property

Devuelve o establece la fuente utilizada en caso de que no se encuentre la fuente fuente. Lectura-escrituraString .

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

### Ver también

* class [SaveOptions](../../saveoptions)
* espacio de nombres [Aspose.Slides.Export](../../saveoptions)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->