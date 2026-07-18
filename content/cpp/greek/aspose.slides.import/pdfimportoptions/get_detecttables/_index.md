---
title: get_DetectTables()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει εάν εντοπίζει πίνακες κατά την εισαγωγή αρχείου PDF.
type: docs
weight: 1
url: /el/aspose.slides.import/pdfimportoptions/get_detecttables/
---
## PdfImportOptions::get_DetectTables() const μέθοδος


Καθορίζει εάν εντοπίζει πίνακες κατά την εισαγωγή αρχείου PDF.

```cpp
bool Aspose::Slides::Import::PdfImportOptions::get_DetectTables() const
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