---
title: get_CompressionLevel()
second_title: Αναφορά API Aspose.Slides για C++
description: "Καθορίζει το επίπεδο συμπίεσης που χρησιμοποιείται κατά την αποθήκευση του εγγράφου παρουσίασης. Η προεπιλεγμένη τιμή είναι CompressionLevel::Level6."
type: docs
weight: 79
url: /el/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() μέθοδος

Καθορίζει το επίπεδο συμπίεσης που χρησιμοποιείται κατά την αποθήκευση του εγγράφου παρουσίασης. Η προεπιλεγμένη τιμή είναι [CompressionLevel::Level6](../../compressionlevel/).

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## Παρατηρήσεις

Τα υψηλότερα επίπεδα συμπίεσης παράγουν μικρότερα αρχεία, αλλά απαιτούν περισσότερη επεξεργαστική ώρα. Ο πραγματικός λόγος συμπίεσης εξαρτάται από το περιεχόμενο της παρουσίασης. 

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## Δείτε επίσης

* Enum [CompressionLevel](../../compressionlevel/)
* Κλάση [PptxOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)