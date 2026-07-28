---
title: set_Handout()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa, ile slajdów i w jakiej kolejności zostanie umieszczonych na stronie HandoutType.
type: docs
weight: 14
url: /pl/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) metoda


Określa, ile slajdów i w jakiej kolejności zostanie umieszczonych na stronie [HandoutType](../../handouttype/).

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
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
* Biblioteka [Aspose.Slides](../../../)