---
title: get_HideInk()
second_title: Aspose.Slides for C++ API Referencia
description: Megjeleníti vagy elrejti az Ink elemeket az exportált dokumentumban.
type: docs
weight: 1
url: /hu/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() metódus


Megjeleníti vagy elrejti a [Ink](../../../aspose.slides.ink/) elemeket az exportált dokumentumban.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## Megjegyzések


Alapértelmezett érték hamis. 

A következő példa bemutatja, hogyan lehet elrejteni a [Ink](../../../aspose.slides.ink/) elemeket az exportált PDF dokumentumban: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Lásd még

* Class [InkOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)