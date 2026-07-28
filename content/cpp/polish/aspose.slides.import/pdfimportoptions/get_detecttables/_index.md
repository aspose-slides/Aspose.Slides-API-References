---
title: get_DetectTables()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Określa, czy wykrywać tabele podczas importowania pliku PDF.
type: docs
weight: 1
url: /pl/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const metoda

Określa, czy wykrywać tabele podczas importowania pliku PDF.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## Uwagi

Przykład:

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Klasa [PdfImportOptions](../)
* Przestrzeń nazw [Aspose::Slides::Import](../../)
* Biblioteka [Aspose.Slides](../../../)