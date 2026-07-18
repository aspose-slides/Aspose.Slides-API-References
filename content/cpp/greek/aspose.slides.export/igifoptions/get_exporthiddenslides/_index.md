---
title: get_ExportHiddenSlides()
second_title: Αναφορά API του Aspose.Slides για C++
description: Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν. Η προεπιλεγμένη τιμή είναι false.
type: docs
weight: 27
url: /el/aspose.slides.export/igifoptions/get_exporthiddenslides/
---
## IGifOptions::get_ExportHiddenSlides() μέθοδος


Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν. Η προεπιλεγμένη τιμή είναι false.

```cpp
virtual bool Aspose::Slides::Export::IGifOptions::get_ExportHiddenSlides()=0
```

## Παρατηρήσεις



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Δείτε επίσης

* Κλάση [IGifOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)