---
title: get_CompressionLevel()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Καθορίζει το επίπεδο συμπίεσης που χρησιμοποιείται κατά την αποθήκευση του εγγράφου παρουσίασης. Η προεπιλεγμένη τιμή είναι CompressionLevel::Level6."
type: docs
weight: 79
url: /el/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() μέθοδος


Καθορίζει το επίπεδο συμπίεσης που χρησιμοποιείται κατά την αποθήκευση του εγγράφου παρουσίασης. Η προεπιλεγμένη τιμή είναι [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## Παρατηρήσεις


Τα υψηλότερα επίπεδα συμπίεσης παράγουν μικρότερα αρχεία, αλλά απαιτούν περισσότερο χρόνο επεξεργασίας. Ο πραγματικός λόγος συμπίεσης εξαρτάται από το περιεχόμενο της παρουσίασης. 

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Δείτε επίσης

* Enum [CompressionLevel](../../compressionlevel/)
* Κλάση [IPptxOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)