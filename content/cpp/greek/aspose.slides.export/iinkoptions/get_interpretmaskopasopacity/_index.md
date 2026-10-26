---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides για C++ API Αναφορά
description: Χρησιμοποιεί λειτουργία ROP ή Opacity για την απόδοση του πινέλου.
type: docs
weight: 27
url: /el/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() μέθοδος


Χρησιμοποιεί λειτουργία ROP ή Opacity για την απόδοση του πινέλου.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## Παρατηρήσεις


Η προεπιλεγμένη τιμή είναι true. 

Το επόμενο παράδειγμα δείχνει πώς να ορίσετε τη χρήση ROP για την εξαγωγή των στοιχείων [Ink](../../../aspose.slides.ink/):

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Δείτε επίσης

* Κλάση [IInkOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)