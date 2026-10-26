---
title: set_InterpretMaskOpAsOpacity()
second_title: Αναφορά API Aspose.Slides για C++
description: Χρησιμοποιεί λειτουργία ROP ή Opacity για την απόδοση του πινέλου.
type: docs
weight: 40
url: /el/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) μέθοδος

Χρησιμοποιεί λειτουργία ROP ή Opacity για την απόδοση του πινέλου.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
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