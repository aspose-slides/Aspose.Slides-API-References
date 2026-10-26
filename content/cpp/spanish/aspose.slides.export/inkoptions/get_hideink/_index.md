---
title: get_HideInk()
second_title: Referencia de la API de Aspose.Slides para C++
description: Muestra u oculta elementos Ink en el documento exportado.
type: docs
weight: 1
url: /es/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() método


Muestra u oculta [Ink](../../../aspose.slides.ink/) elementos en el documento exportado.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## Observaciones


El valor predeterminado es false. 

El siguiente ejemplo muestra cómo ocultar [Ink](../../../aspose.slides.ink/) elementos en un documento PDF exportado: 
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