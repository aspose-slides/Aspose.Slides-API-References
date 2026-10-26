---
title: get_HideInk()
second_title: Referencia de API de Aspose.Slides para C++
description: Muestra u oculta los elementos Ink en el documento exportado.
type: docs
weight: 1
url: /es/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() método

Muestra u oculta elementos [Ink](../../../aspose.slides.ink/) en el documento exportado.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## Observaciones

El valor predeterminado es false.

El siguiente ejemplo muestra cómo ocultar elementos [Ink](../../../aspose.slides.ink/) en un documento PDF exportado:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Ver también

* Clase [IInkOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)