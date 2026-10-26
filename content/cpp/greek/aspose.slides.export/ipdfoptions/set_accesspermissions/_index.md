---
title: set_AccessPermissions()
second_title: Aspose.Slides για C++ Αναφορά API
description: Περιέχει ένα σύνολο σημαιών που καθορίζουν ποια δικαιώματα πρόσβασης πρέπει να παραχωρηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. Δείτε PdfAccessPermissions.
type: docs
weight: 274
url: /el/aspose.slides.export/ipdfoptions/set_accesspermissions/
---
## IPdfOptions::set_AccessPermissions(PdfAccessPermissions) μέθοδος

Περιέχει ένα σύνολο θυρών που καθορίζουν ποια δικαιώματα πρόσβασης πρέπει να παραχωρηθούν όταν το έγγραφο ανοίγει με πρόσβαση χρήστη. Δείτε [PdfAccessPermissions](../../pdfaccesspermissions/).

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_AccessPermissions(PdfAccessPermissions value)=0
```

## Σχόλια


```cpp
auto pdfOptions = MakeObject<PdfOptions>();
pdfOptions->set_Password(u"my_password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
auto presentation = MakeObject<Presentation>();
presentation->Save(pdfFilePath, SaveFormat::Pdf, pdfOptions);
```

## Δείτε επίσης

* Απαρίθμηση [PdfAccessPermissions](../../pdfaccesspermissions/)
* Κλάση [IPdfOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)