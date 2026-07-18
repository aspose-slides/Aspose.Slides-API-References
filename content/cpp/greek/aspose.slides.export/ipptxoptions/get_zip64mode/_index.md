---
title: get_Zip64Mode()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Καθορίζει εάν η μορφή ZIP64 χρησιμοποιείται για το έγγραφο Παρουσίασης. Η προεπιλεγμένη τιμή είναι Zip64Mode::IfNecessary"
type: docs
weight: 27
url: /el/aspose.slides.export/ipptxoptions/get_zip64mode/
---
## IPptxOptions::get_Zip64Mode() μέθοδος

Καθορίζει εάν η μορφή ZIP64 χρησιμοποιείται για το έγγραφο [Presentation](../../../aspose.slides/presentation/). Η προεπιλεγμένη τιμή είναι [Zip64Mode::IfNecessary](../../zip64mode/)

```cpp
virtual Aspose::Slides::Export::Zip64Mode Aspose::Slides::Export::IPptxOptions::get_Zip64Mode()=0
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