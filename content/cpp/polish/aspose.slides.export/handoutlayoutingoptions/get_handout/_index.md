---
title: get_Handout()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Określa, ile slajdów i w jakiej kolejności zostanie umieszczonych na stronie HandoutType.
type: docs
weight: 1
url: /pl/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const metoda


Określa, ile slajdów i w jakiej kolejności zostanie umieszczonych na stronie [HandoutType](../../handouttype/).

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
```

## Uwagi


Domyślna wartość to **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Zobacz także

* Enum [HandoutType](../../handouttype/)
* Klasa [HandoutLayoutingOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)