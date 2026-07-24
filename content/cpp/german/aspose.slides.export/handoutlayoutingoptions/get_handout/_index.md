---
title: get_Handout()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt an, wie viele Folien und in welcher Reihenfolge auf der Seite HandoutType platziert werden.
type: docs
weight: 1
url: /de/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const Methode

Gibt an, wie viele Folien und in welcher Reihenfolge auf der Seite [HandoutType](../../handouttype/) platziert werden.

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
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

* Aufzählung [HandoutType](../../handouttype/)
* Klasse [HandoutLayoutingOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)