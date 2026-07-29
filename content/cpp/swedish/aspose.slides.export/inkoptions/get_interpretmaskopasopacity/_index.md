---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides för C++ API-referens
description: Använder ROP-operation eller Opacity för att rendera penseln.
type: docs
weight: 27
url: /sv/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() metod


Använder ROP-operation eller Opacity för att rendera penseln.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## Anmärkningar


Standardvärdet är true. 

Nästa exempel visar hur man ställer in med ROP för att exportera [Ink](../../../aspose.slides.ink/) element: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Se även

* Klass [InkOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)