---
title: set_RefreshThumbnail()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Καθορίζει εάν η μικρογραφία της παρουσίασης θα ανανεωθεί. Γράψτε bool. Η προεπιλεγμένη τιμή είναι true.
type: docs
weight: 66
url: /el/aspose.slides.export/pptxoptions/set_refreshthumbnail/
---
## PptxOptions::set_RefreshThumbnail(bool) method

Καθορίζει εάν η μικρογραφία της παρουσίασης θα ανανεωθεί. Γράψτε **bool**. Η προεπιλεγμένη τιμή είναι **true**.

```cpp
void Aspose::Slides::Export::PptxOptions::set_RefreshThumbnail(bool value) override
```

## Παρατηρήσεις

Όταν η τιμή της επιλογής είναι **true**, η νέα μικρογραφία θα παραχθεί.

Όταν η τιμή της επιλογής είναι **false**, η τρέχουσα μικρογραφία θα αποθηκευθεί όπως είναι.

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Δείτε επίσης

* Κλάση [PptxOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)