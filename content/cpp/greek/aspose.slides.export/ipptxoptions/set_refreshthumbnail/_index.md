---
title: set_RefreshThumbnail()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει εάν η μικρογραφία της παρουσίασης θα ανανεωθεί. Γράψτε bool. Η προεπιλεγμένη τιμή είναι true.
type: docs
weight: 66
url: /el/aspose.slides.export/ipptxoptions/set_refreshthumbnail/
---
## IPptxOptions::set_RefreshThumbnail(bool) μέθοδος

Καθορίζει εάν η μικρογραφία της παρουσίασης θα ανανεωθεί. Γράψτε **bool**. Η προεπιλεγμένη τιμή είναι **true**.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_RefreshThumbnail(bool value)=0
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

* Κλάση [IPptxOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)