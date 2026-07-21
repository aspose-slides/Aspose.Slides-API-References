---
title: get_Handout()
second_title: Справочник API Aspose.Slides для C++
description: Указывает, сколько слайдов и в какой последовательности будет размещено на странице HandoutType.
type: docs
weight: 1
url: /ru/aspose.slides.export/handoutlayoutingoptions/get_handout/
---
## HandoutLayoutingOptions::get_Handout() const метод


Указывает, сколько слайдов и в какой последовательности будет размещено на странице [HandoutType](../../handouttype/).

```cpp
HandoutType Aspose::Slides::Export::HandoutLayoutingOptions::get_Handout() const
```

## Примечания


Значение по умолчанию — **[HandoutType::Handouts6Horizontal](../../handouttype/)**. 

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## См. также

* Enum [HandoutType](../../handouttype/)
* Class [HandoutLayoutingOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)