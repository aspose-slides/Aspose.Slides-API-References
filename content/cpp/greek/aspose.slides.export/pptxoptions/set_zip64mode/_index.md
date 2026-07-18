---
title: set_Zip64Mode()
second_title: Aspose.Slides για την Αναφορά API C++
description: "Καθορίζει εάν η μορφή ZIP64 χρησιμοποιείται για το έγγραφο Presentation. Η προεπιλεγμένη τιμή είναι Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /el/aspose.slides.export/pptxoptions/set_zip64mode/
---
## PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) μέθοδος

Καθορίζει εάν η μορφή ZIP64 χρησιμοποιείται για το έγγραφο [Presentation](../../../aspose.slides/presentation/). Η προεπιλεγμένη τιμή είναι [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
void Aspose::Slides::Export::PptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value) override
```
## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_Zip64Mode(Zip64Mode::Always);
pres->Save(u"demo-zip64.pptx", SaveFormat::Pptx, pptxOptions);
```

## Δείτε επίσης

* Απαρίθμηση [Zip64Mode](../../zip64mode/)
* Κλάση [PptxOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)