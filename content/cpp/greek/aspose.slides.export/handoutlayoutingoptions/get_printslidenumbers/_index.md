---
title: get_PrintSlideNumbers()
second_title: Αναφορά API του Aspose.Slides για C++
description: Καθορίζει αν θα εκτυπωθούν ή όχι οι εμφανιζόμενοι αριθμοί διαφανειών.
type: docs
weight: 27
url: /el/aspose.slides.export/handoutlayoutingoptions/get_printslidenumbers/
---
## HandoutLayoutingOptions::get_PrintSlideNumbers() const μέθοδος


Καθορίζει εάν θα εκτυπωθούν ή όχι οι εμφανιζόμενοι αριθμοί διαφανειών.

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintSlideNumbers() const
```

## Παρατηρήσεις


Η προεπιλεγμένη τιμή είναι **true**. 

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintSlideNumbers(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Δείτε επίσης

* Κλάση [HandoutLayoutingOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)