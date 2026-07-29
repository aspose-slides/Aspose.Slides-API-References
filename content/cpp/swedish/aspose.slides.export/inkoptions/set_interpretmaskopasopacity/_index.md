---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides för C++ API-referens
description: Använder ROP-operation eller opacitet för rendering av pensel.
type: docs
weight: 40
url: /sv/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) metod

Använder ROP-operation eller opacitet för rendering av pensel.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## Anmärkningar

Standardvärdet är true.

Nästa exempel visar hur man ställer in med ROP för att exportera [Ink](../../../aspose.slides.ink/)-element:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Se också

* Klass [InkOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)