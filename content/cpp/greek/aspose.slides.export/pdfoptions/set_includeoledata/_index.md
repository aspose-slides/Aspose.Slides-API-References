---
title: set_IncludeOleData()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αληθές για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Γράψτε bool.
type: docs
weight: 469
url: /el/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) μέθοδος


Αληθές για τη μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Γράψτε **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
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
* Ονομαχώρος [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)