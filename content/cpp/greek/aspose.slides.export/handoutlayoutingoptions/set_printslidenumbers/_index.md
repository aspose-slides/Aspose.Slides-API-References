---
title: set_PrintSlideNumbers()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει εάν θα εκτυπώνονται ή όχι οι εμφανιζόμενοι αριθμοί διαφανειών.
type: docs
weight: 40
url: /el/aspose.slides.export/handoutlayoutingoptions/set_printslidenumbers/
---
## HandoutLayoutingOptions::set_PrintSlideNumbers(bool) μέθοδος

Καθορίζει αν θα εκτυπώνονται ή όχι οι εμφανιζόμενοι αριθμοί των διαφανειών.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintSlideNumbers(bool value)
```

## Σχόλια

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