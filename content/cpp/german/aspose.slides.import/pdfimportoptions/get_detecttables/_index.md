---
title: get_DetectTables()
second_title: Aspose.Slides für C++ API Referenz
description: Bestimmt, ob beim Importieren einer PDF-Datei Tabellen erkannt werden.
type: docs
weight: 1
url: /de/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const Methode


Bestimmt, ob beim Importieren einer PDF-Datei Tabellen erkannt werden.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
```

## Hinweise


Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [PdfImportOptions](../)
* Namensraum [Aspose::Slides::Import](../../)
* Bibliothek [Aspose.Slides](../../../)