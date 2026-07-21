---
title: set_Handout()
second_title: Aspose.Slides для C++ справочник API
description: Указывает, сколько слайдов и в каком порядке будут размещены на странице HandoutType.
type: docs
weight: 14
url: /ru/aspose.slides.export/handoutlayoutingoptions/set_handout/
---
## HandoutLayoutingOptions::set_Handout(HandoutType) метод


Указывает, сколько слайдов и в каком порядке будут размещены на странице [HandoutType](../../handouttype/).

```cpp
void Aspose::Slides::Export::HandoutLayoutingOptions::set_Handout(HandoutType value)
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

* Перечисление [HandoutType](../../handouttype/)
* Класс [HandoutLayoutingOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)