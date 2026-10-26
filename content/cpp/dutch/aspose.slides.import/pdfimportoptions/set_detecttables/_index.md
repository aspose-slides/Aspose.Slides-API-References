---
title: set_DetectTables()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of tabellen worden gedetecteerd bij het importeren van een pdf-bestand.
type: docs
weight: 14
url: /nl/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) methode


Bepaalt of tabellen worden gedetecteerd bij het importeren van een pdf-bestand.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Zie ook

* Klasse [PdfImportOptions](../)
* Naamruimte [Aspose::Slides::Import](../../)
* Bibliotheek [Aspose.Slides](../../../)