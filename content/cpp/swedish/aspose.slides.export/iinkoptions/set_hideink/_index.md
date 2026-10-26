---
title: set_HideInk()
second_title: Aspose.Slides för C++ API-referens
description: Visar eller döljer Ink-element i exporterat dokument.
type: docs
weight: 14
url: /sv/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) metod


Visar eller döljer [Ink](../../../aspose.slides.ink/) element i exporterat dokument.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## Anmärkningar


Standardvärdet är false. 

Nästa exempel visar hur man döljer [Ink](../../../aspose.slides.ink/) element i exporterat PDF-dokument: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Se också

* Klass [IInkOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)