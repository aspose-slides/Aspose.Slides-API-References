---
title: get_HideInk()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εμφανίζει ή κρύβει στοιχεία Ink σε εξαγόμενο έγγραφο.
type: docs
weight: 1
url: /el/aspose.slides.export/iinkoptions/get_hideink/
---
## IInkOptions::get_HideInk() μέθοδος

Εμφανίζει ή κρύβει στοιχεία [Ink](../../../aspose.slides.ink/) σε εξαγόμενο έγγραφο.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_HideInk()=0
```

## Παρατηρήσεις

Η προεπιλεγμένη τιμή είναι false. 

Το επόμενο παράδειγμα δείχνει πώς να κρύψετε στοιχεία [Ink](../../../aspose.slides.ink/) σε εξαγόμενο έγγραφο PDF: 
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