---
title: set_Handout()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Určuje, kolik snímků a v jakém pořadí budou umístěny na stránku HandoutType.
type: docs
weight: 14
url: /cs/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) metoda


Určuje, kolik snímků a v jakém pořadí bude umístěno na stránce [HandoutType](../../handouttype/).

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
```

## Poznámky


Výchozí hodnota je **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Viz také

* Výčet [HandoutType](../../handouttype/)
* Třída [HandoutLayoutingOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)