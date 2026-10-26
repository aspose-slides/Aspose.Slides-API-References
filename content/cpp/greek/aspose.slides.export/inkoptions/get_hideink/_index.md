---
title: get_HideInk()
second_title: Αναφορά API του Aspose.Slides για C++
description: Εμφανίζει ή κρύβει στοιχεία Ink σε εξαγόμενο έγγραφο.
type: docs
weight: 1
url: /el/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() μέθοδος

Εμφανίζει ή κρύβει στοιχεία [Ink](../../../aspose.slides.ink/) σε εξαγόμενο έγγραφο.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## Σχόλια

Η προεπιλεγμένη τιμή είναι false.

Το επόμενο παράδειγμα δείχνει πώς να κρύψετε στοιχεία [Ink](../../../aspose.slides.ink/) σε εξαγόμενο έγγραφο PDF:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Δείτε επίσης

* Κλάση [InkOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)