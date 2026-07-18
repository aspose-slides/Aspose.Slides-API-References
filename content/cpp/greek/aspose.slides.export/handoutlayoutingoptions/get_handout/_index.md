---
title: get_Handout()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει πόσες διαφάνειες και με ποια σειρά θα τοποθετηθούν στη σελίδα HandoutType.
type: docs
weight: 1
url: /el/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const μέθοδος

Καθορίζει πόσες διαφάνειες και με ποια σειρά θα τοποθετηθούν στη σελίδα [HandoutType](../../handouttype/).

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
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