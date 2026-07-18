---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides για C++ Αναφορά API
description: Χρησιμοποιεί λειτουργία ROP ή Opacity για την απόδοση της βούρτσας.
type: docs
weight: 27
url: /el/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() μέθοδος


Χρησιμοποιεί τη λειτουργία ROP ή το Opacity για την απόδοση της βούρτσας.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## Παρατηρήσεις


Η προεπιλεγμένη τιμή είναι true. 

Το επόμενο παράδειγμα δείχνει πώς να ορίσετε τη χρήση του ROP για την εξαγωγή των στοιχείων [Ink](../../../aspose.slides.ink/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## Δείτε επίσης

* Κλάση [InkOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)