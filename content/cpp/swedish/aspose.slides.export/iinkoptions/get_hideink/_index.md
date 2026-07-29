---
title: get_HideInk()
second_title: Aspose.Slides för C++ API-referens
description: Visar eller döljer bläckelement i exporterat dokument.
type: docs
weight: 1
url: /sv/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() metod


Visar eller döljer [Ink](../../../aspose.slides.ink/) element i exporterat dokument.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## Anmärkningar


Standardvärdet är false. 

Nästa exempel visar hur du döljer [Ink](../../../aspose.slides.ink/) element i exporterat PDF-dokument: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Se även

* Klass [IInkOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)