---
title: get_DetectTables()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om tabeller ska upptäckas vid import av PDF-fil.
type: docs
weight: 1
url: /sv/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const metod


Fastställer om tabeller ska upptäckas vid import av PDF-fil.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [PdfImportOptions](../)
* Namnrymd [Aspose::Slides::Import](../../)
* Bibliotek [Aspose.Slides](../../../)