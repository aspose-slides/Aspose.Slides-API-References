---
title: set_Zip64Mode()
second_title: Αναφορά API Aspose.Slides για C++
description: "Καθορίζει αν η μορφή ZIP64 χρησιμοποιείται για το έγγραφο Presentation. Η προεπιλεγμένη τιμή είναι Zip64Mode::IfNecessary"
type: docs
weight: 40
url: /el/aspose.slides.export/ipptxoptions/set_zip64mode/
---
## IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode) μέθοδος

Καθορίζει αν η μορφή ZIP64 χρησιμοποιείται για το έγγραφο [Presentation](../../../aspose.slides/presentation/). Η προεπιλεγμένη τιμή είναι [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_Zip64Mode(Aspose::Slides::Export::Zip64Mode value)=0
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
* Κλάση [IPptxOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)