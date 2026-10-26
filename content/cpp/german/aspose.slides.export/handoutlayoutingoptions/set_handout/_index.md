---
title: set_Handout()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie viele Folien und in welcher Reihenfolge auf der Seite HandoutType platziert werden.
type: docs
weight: 14
url: /de/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) Methode


Gibt an, wie viele Folien und in welcher Reihenfolge auf der Seite [HandoutType](../../handouttype/) platziert werden.

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
```

## Hinweise


Standardwert ist **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Siehe auch

* Enum [HandoutType](../../handouttype/)
* Klasse [HandoutLayoutingOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)