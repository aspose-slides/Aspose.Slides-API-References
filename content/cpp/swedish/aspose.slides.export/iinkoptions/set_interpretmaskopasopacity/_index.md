---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides för C++ API-referens
description: Använder ROP-operation eller opacitet för att rendera penseln.
type: docs
weight: 40
url: /sv/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) metod


Använder ROP operation eller opacitet för rendering av pensel.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## Anmärkningar


Standardvärdet är true. 

Nästa exempel demonstrerar hur man ställer in att använda ROP för att exportera [Ink](../../../aspose.slides.ink/) element: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Se även

* Klass [IInkOptions](../)
* Namnutrymme [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)