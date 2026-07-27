---
title: set_HideInk()
second_title: Referencia de la API de Aspose.Slides para C++
description: Muestra u oculta elementos Ink en el documento exportado.
type: docs
weight: 14
url: /es/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) método

Muestra u oculta los elementos [Ink](../../../aspose.slides.ink/) en el documento exportado.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## Observaciones

El valor predeterminado es false.

El siguiente ejemplo muestra cómo ocultar los elementos [Ink](../../../aspose.slides.ink/) en un documento PDF exportado:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Ver también

* Clase [InkOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)