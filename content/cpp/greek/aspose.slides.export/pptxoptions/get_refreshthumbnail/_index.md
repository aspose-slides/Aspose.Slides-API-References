---
title: get_RefreshThumbnail()
second_title: Aspose.Slides για την Αναφορά API C++
description: Καθορίζει εάν η μικρογραφία της παρουσίασης θα ανανεωθεί. Διαβάστε bool. Η προεπιλεγμένη τιμή είναι true.
type: docs
weight: 53
url: /el/aspose.slides.export/pptxoptions/get_refreshthumbnail/
---
## PptxOptions::get_RefreshThumbnail() μέθοδος

Καθορίζει εάν η μικρογραφία της παρουσίασης θα ανανεωθεί. Διαβάστε **bool**. Η προεπιλεγμένη τιμή είναι **true**.

```cpp
bool Aspose::Slides::Export::PptxOptions::get_RefreshThumbnail() override
```

## Παρατηρήσεις

Όταν η τιμή της επιλογής είναι **true**, η νέα μικρογραφία θα δημιουργηθεί.

Όταν η τιμή της επιλογής είναι **false**, η τρέχουσα μικρογραφία θα αποθηκευτεί όπως είναι.

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