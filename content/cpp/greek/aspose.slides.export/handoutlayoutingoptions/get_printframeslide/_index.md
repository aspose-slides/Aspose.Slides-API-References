---
title: get_PrintFrameSlide()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει αν θα σχεδιάζονται πλαίσια γύρω από τις εμφανιζόμενες διαφάνειες ή όχι.
type: docs
weight: 53
url: /el/aspose.slides.export/handoutlayoutingoptions/get_printframeslide/
---
## HandoutLayoutingOptions::get_PrintFrameSlide() const μέθοδος

Καθορίζει αν θα σχεδιάζονται περιγράμματα γύρω από τις εμφανιζόμενες διαφάνειες ή όχι.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintFrameSlide() const
```

## Παρατηρήσεις

Η προεπιλεγμένη τιμή είναι **true**. 

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintFrameSlide(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Δείτε επίσης

* Τάξη [HandoutLayoutingOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)