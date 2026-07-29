---
title: set_DetectTables()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om tabeller ska upptäckas när PDF-filen importeras.
type: docs
weight: 14
url: /sv/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) metod


Bestämmer om tabeller ska upptäckas när PDF-filen importeras.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
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

## Se också

* Klass [PdfImportOptions](../)
* Namnrymd [Aspose::Slides::Import](../../)
* Bibliotek [Aspose.Slides](../../../)