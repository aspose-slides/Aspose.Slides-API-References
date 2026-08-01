---
title: set_PrintSlideNumbers()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft aan of de weergegeven dia-nummers al dan niet afgedrukt moeten worden.
type: docs
weight: 40
url: /nl/aspose.slides.export/handoutlayoutingoptions/set_printslidenumbers/
---
## HandoutLayoutingOptions::set_PrintSlideNumbers(bool) method

Geeft aan of de weergegeven dia-nummers al dan niet afgedrukt moeten worden.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintSlideNumbers(bool value)
```

## Opmerkingen

Standaardwaarde is **true**. 

Voorbeeld: 
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

## Zie ook

* Class [HandoutLayoutingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)