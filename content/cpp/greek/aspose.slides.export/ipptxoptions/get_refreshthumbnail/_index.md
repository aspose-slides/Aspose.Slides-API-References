---
title: get_RefreshThumbnail()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει αν η μικρογραφία της παρουσίασης θα ανανεωθεί. Διαβάζει bool. Η προεπιλεγμένη τιμή είναι true.
type: docs
weight: 53
url: /el/aspose.slides.export/ipptxoptions/get_refreshthumbnail/
---
## IPptxOptions::get_RefreshThumbnail() μέθοδος


Καθορίζει αν η μικρογραφία της παρουσίασης θα ανανεωθεί. Διαβάζει **bool**. Η προεπιλεγμένη τιμή είναι **true**.

```cpp
virtual bool Aspose::Slides::Export::IPptxOptions::get_RefreshThumbnail()=0
```

## Παρατηρήσεις


Όταν η τιμή της επιλογής είναι **true**, θα δημιουργηθεί η νέα μικρογραφία.

Όταν η τιμή της επιλογής είναι **false**, η τρέχουσα μικρογραφία θα αποθηκευτεί όπως είναι.

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_RefreshThumbnail(false);
pres->Save(u"result_with_old_thumbnail.pptx", SaveFormat::Pptx, pptxOptions);
```

## Δείτε επίσης

* Κλάση [IPptxOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)