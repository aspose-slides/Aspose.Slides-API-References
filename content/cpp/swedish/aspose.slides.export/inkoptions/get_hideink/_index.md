---
title: get_HideInk()
second_title: Aspose.Slides för C++ API-referens
description: Visar eller döljer Ink-element i exporterat dokument.
type: docs
weight: 1
url: /sv/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() metod

Visar eller döljer [Ink](../../../aspose.slides.ink/) element i exporterat dokument.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## Anmärkningar

Standardvärdet är falskt. 

Nästa exempel demonstrerar hur man döljer [Ink](../../../aspose.slides.ink/) element i exporterat PDF-dokument: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Se även

* Klass [InkOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)