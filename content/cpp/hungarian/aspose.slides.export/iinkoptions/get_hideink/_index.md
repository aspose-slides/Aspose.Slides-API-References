---
title: get_HideInk()
second_title: Aspose.Slides for C++ API referenciája
description: Megjeleníti vagy elrejti az Ink elemeket az exportált dokumentumban.
type: docs
weight: 1
url: /hu/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() metódus

Megjeleníti vagy elrejti a [Ink](../../../aspose.slides.ink/) elemeket az exportált dokumentumban.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## Megjegyzés

Az alapértelmezett érték false.

A következő példa bemutatja, hogyan lehet elrejteni a [Ink](../../../aspose.slides.ink/) elemeket az exportált PDF dokumentumban:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Lásd még

* Osztály [IInkOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)