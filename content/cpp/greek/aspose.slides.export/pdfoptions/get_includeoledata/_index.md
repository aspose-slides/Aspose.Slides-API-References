---
title: get_IncludeOleData()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αληθές για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Ανάγνωση bool.
type: docs
weight: 456
url: /el/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() μέθοδος


Αληθές για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Ανάγνωση **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## Παρατηρήσεις


Η προεπιλογή είναι **false**. 

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Δείτε επίσης

* Κλάση [PdfOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)