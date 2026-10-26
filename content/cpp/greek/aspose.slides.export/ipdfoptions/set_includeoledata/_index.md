---
title: set_IncludeOleData()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αληθές για μετατροπή όλων των δεδομένων OLE από την παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Γράψτε bool.
type: docs
weight: 469
url: /el/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) μέθοδος

Αληθές για μετατροπή όλων των δεδομένων OLE από η παρουσίαση σε ενσωματωμένα αρχεία στο παραγόμενο PDF. Γράψτε **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
```

## Παρατηρήσεις

Προεπιλογή είναι **false**. 

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## Δείτε επίσης

* Κλάση [IPdfOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)