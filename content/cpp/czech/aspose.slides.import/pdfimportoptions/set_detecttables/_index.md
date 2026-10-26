---
title: set_DetectTables()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Určuje, zda detekovat tabulky při importu souboru PDF.
type: docs
weight: 14
url: /cs/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) metoda


Určuje, zda detekovat tabulky při importu souboru pdf.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
```

## Poznámky


Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Viz také

* Třída [PdfImportOptions](../)
* Jmenný prostor [Aspose::Slides::Import](../../)
* Knihovna [Aspose.Slides](../../../)