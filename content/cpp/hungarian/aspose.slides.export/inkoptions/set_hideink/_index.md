---
title: set_HideInk()
second_title: Aspose.Slides C++ API referencia
description: Megjeleníti vagy elrejti az Ink elemeket az exportált dokumentumban.
type: docs
weight: 14
url: /hu/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) metódus

Megjeleníti vagy elrejti [Ink](../../../aspose.slides.ink/) elemeket az exportált dokumentumban.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## Megjegyzések

Az alapértelmezett érték false.

A következő példa bemutatja, hogyan lehet elrejteni [Ink](../../../aspose.slides.ink/) elemeket az exportált PDF dokumentumban:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Lásd még

* Osztály [InkOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)