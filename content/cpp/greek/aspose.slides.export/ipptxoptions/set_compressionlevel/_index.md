---
title: set_CompressionLevel()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Καθορίζει το επίπεδο συμπίεσης που χρησιμοποιείται κατά την αποθήκευση του εγγράφου παρουσίασης. Η προεπιλεγμένη τιμή είναι CompressionLevel::Level6."
type: docs
weight: 92
url: /el/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) μέθοδος

Καθορίζει το επίπεδο συμπίεσης που χρησιμοποιείται κατά την αποθήκευση του εγγράφου παρουσίασης. Η προεπιλεγμένη τιμή είναι [CompressionLevel::Level6](../../compressionlevel/).

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## Παρατηρήσεις

Τα υψηλότερα επίπεδα συμπίεσης παράγουν μικρότερα αρχεία αλλά απαιτούν περισσότερο χρόνο επεξεργασίας. Ο πραγματικός λόγος συμπίεσης εξαρτάται από το περιεχόμενο της παρουσίασης.  

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Δείτε επίσης

* Απαριθμήσι [CompressionLevel](../../compressionlevel/)
* Κλάση [IPptxOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)