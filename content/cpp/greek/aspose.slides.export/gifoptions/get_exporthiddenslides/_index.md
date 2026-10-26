---
title: get_ExportHiddenSlides()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν. Η προεπιλεγμένη τιμή είναι false.
type: docs
weight: 27
url: /el/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() μέθοδος


Καθορίζει εάν οι κρυφές διαφάνειες θα εξαχθούν. Η προεπιλεγμένη τιμή είναι false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## Παρατηρήσεις



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Δείτε επίσης

* Κλάση [GifOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)