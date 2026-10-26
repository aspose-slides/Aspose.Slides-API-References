---
title: set_HideInk()
second_title: Aspose.Slides για C++ Αναφορά API
description: Εμφανίζει ή κρύβει τα στοιχεία Ink στο εξαγόμενο έγγραφο.
type: docs
weight: 14
url: /el/aspose.slides.export/inkoptions/set_hideink/
---
## InkOptions::set_HideInk(bool) μέθοδος

Εμφανίζει ή κρύβει τα στοιχεία [Ink](../../../aspose.slides.ink/) στο εξαγόμενο έγγραφο.

```cpp
void Aspose::Slides::Export::InkOptions::set_HideInk(bool value) override
```

## Σχόλια

Η προεπιλεγμένη τιμή είναι false.

Το επόμενο παράδειγμα δείχνει πώς να κρύψετε τα στοιχεία [Ink](../../../aspose.slides.ink/) στο εξαγόμενο έγγραφο PDF:
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