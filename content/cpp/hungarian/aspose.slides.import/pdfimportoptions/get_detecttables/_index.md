---
title: get_DetectTables()
second_title: Aspose.Slides C++ API Referencia
description: Meghatározza, hogy a PDF-fájl importálásakor felismerje-e a táblázatokat.
type: docs
weight: 1
url: /hu/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const metódus


Meghatározza, hogy a PDF-fájl importálásakor felismerje-e a táblázatokat.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## Megjegyzés


Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Lásd még

* Osztály [PdfImportOptions](../)
* Névterület [Aspose::Slides::Import](../../)
* Könyvtár [Aspose.Slides](../../../)