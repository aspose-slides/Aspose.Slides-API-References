---
title: set_DetectTables()
second_title: Aspose.Slides für C++ API-Referenz
description: Bestimmt, ob Tabellen beim Importieren einer PDF-Datei erkannt werden.
type: docs
weight: 14
url: /de/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) Methode

Bestimmt, ob Tabellen beim Importieren einer PDF-Datei erkannt werden.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
```

## Bemerkungen

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