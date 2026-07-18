---
title: set_AccessPermissions()
second_title: Aspose.Slides για C++ Αναφορά API
description: Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να παραχωρηθούν όταν το έγγραφο ανοίγεται με πρόσβαση χρήστη. Δείτε PdfAccessPermissions.
type: docs
weight: 313
url: /el/aspose.slides.export/pdfoptions/set_accesspermissions/
---
## PdfOptions::set_AccessPermissions(PdfAccessPermissions) μέθοδος


Περιέχει ένα σύνολο σημαιών που καθορίζουν ποιες άδειες πρόσβασης πρέπει να παραχωρηθούν όταν το έγγραφο ανοίγεται με πρόσβαση χρήστη. Δείτε [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
void Aspose::Slides::Export::PdfOptions::set_AccessPermissions(PdfAccessPermissions value) override
```

## Παρατηρήσεις



```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Δείτε επίσης

* Απαρίθμηση [PdfAccessPermissions](../../pdfaccesspermissions/)
* Κλάση [PdfOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)