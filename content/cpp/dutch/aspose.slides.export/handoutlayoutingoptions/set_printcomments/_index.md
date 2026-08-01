---
title: set_PrintComments()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert of opmerkingen al dan niet op dia's worden weergegeven
type: docs
weight: 92
url: /nl/aspose.slides.export/handoutlayoutingoptions/set_printcomments/
---
## HandoutLayoutingOptions::set_PrintComments(bool) methode


Specificeert of opmerkingen al dan niet op dia's worden weergegeven

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_PrintComments(bool value)
```

## Opmerkingen


Standaardwaarde is **false**. 

Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pers = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintComments(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Zie ook

* Klasse [HandoutLayoutingOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)