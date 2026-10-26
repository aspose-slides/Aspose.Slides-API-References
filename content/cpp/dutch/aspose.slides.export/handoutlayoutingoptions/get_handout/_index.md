---
title: get_Handout()
second_title: Aspose.Slides voor C++ API Referentie
description: Specificeert hoeveel dia's en in welke volgorde ze op de pagina HandoutType worden geplaatst.
type: docs
weight: 1
url: /nl/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const methode


Specificeert hoeveel dia's en in welke volgorde ze op de pagina [HandoutType](../../handouttype/) worden geplaatst.

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
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
* Klasse [HandoutLayoutingOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)