---
title: set_Handout()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert hoeveel dia's en in welke volgorde ze op de pagina HandoutType worden geplaatst.
type: docs
weight: 14
url: /nl/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) methode


Specificeert hoeveel dia's en in welke volgorde ze op de pagina [HandoutType](../../handouttype/) worden geplaatst.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
```

## Opmerkingen


Standaardwaarde is **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Zie ook

* Enum [HandoutType](../../handouttype/)
* Class [HandoutLayoutingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)