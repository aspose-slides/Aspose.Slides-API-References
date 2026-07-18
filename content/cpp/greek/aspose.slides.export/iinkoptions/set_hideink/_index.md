---
title: set_HideInk()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εμφανίζει ή κρύβει τα στοιχεία Ink σε εξαγόμενο έγγραφο.
type: docs
weight: 14
url: /el/aspose.slides.export/iinkoptions/set_hideink/
---
## IInkOptions::set_HideInk(bool) μέθοδος


Εμφανίζει ή κρύβει τα [Ink](../../../aspose.slides.ink/) στοιχεία σε εξαγώμενο έγγραφο.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_HideInk(bool value)=0
```

## Παρατηρήσεις


Η προεπιλεγμένη τιμή είναι false. 

Το επόμενο παράδειγμα δείχνει πώς να κρύψετε τα [Ink](../../../aspose.slides.ink/) στοιχεία σε εξαγώμενο έγγραφο PDF: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Δείτε επίσης

* Κλάση [IInkOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)