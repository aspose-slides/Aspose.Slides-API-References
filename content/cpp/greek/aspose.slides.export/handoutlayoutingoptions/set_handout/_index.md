---
title: set_Handout()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει πόσες διαφάνειες και με ποια ακολουθία θα τοποθετηθούν στη σελίδα HandoutType.
type: docs
weight: 14
url: /el/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) μέθοδος

Καθορίζει πόσες διαφάνειες και με ποια ακολουθία θα τοποθετηθούν στη σελίδα [HandoutType](../../handouttype/).

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
```

## Παρατηρήσεις

Η προεπιλεγμένη τιμή είναι **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Δείτε επίσης

* Απαρίθμηση [HandoutType](../../handouttype/)
* Κλάση [HandoutLayoutingOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)