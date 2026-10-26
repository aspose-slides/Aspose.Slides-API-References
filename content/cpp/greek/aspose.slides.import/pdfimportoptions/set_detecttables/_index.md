---
title: set_DetectTables()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Καθορίζει εάν εντοπίζονται πίνακες κατά την εισαγωγή αρχείου pdf.
type: docs
weight: 14
url: /el/aspose.slides.import/pdfimportoptions/set_detecttables/
---
## PdfImportOptions::set_DetectTables(bool) method


Καθορίζει εάν εντοπίζονται πίνακες κατά την εισαγωγή αρχείου pdf.

```cpp
void Aspose::Slides::Import::PdfImportOptions::set_DetectTables(bool value)
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
System::SharedPtr<System::IO::Stream> stream = System::MakeObject<System::IO::FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(stream, options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [PdfImportOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Import](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)