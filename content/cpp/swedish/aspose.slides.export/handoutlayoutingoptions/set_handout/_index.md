---
title: set_Handout()
second_title: Aspose.Slides för C++ API-referens
description: Anger hur många bilder som ska placeras på sidan och i vilken ordning HandoutType.
type: docs
weight: 14
url: /sv/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) metod


Anger hur många bilder som ska placeras på sidan och i vilken ordning [HandoutType](../../handouttype/).

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
```

## Anmärkningar


Standardvärdet är **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Se också

* Enum [HandoutType](../../handouttype/)
* Klass [HandoutLayoutingOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)