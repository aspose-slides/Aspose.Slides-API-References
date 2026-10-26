---
title: set_InterpretMaskOpAsOpacity()
second_title: Αναφορά API Aspose.Slides για C++
description: Χρησιμοποιεί λειτουργία ROP ή διαφάνεια για την απόδοση του πινέλου.
type: docs
weight: 40
url: /el/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) μέθοδος

Χρησιμοποιεί λειτουργία ROP ή Διαφάνεια για τη σχεδίαση πινέλου.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
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