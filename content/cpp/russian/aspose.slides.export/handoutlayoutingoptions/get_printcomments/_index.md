---
title: get_PrintComments()
second_title: Aspose.Slides для справки API C++
description: Указывает, следует ли отображать комментарии на слайдах
type: docs
weight: 79
url: /ru/aspose.slides.export/handoutlayoutingoptions/get_printcomments/
---
## HandoutLayoutingOptions::get_PrintComments() const метод

Указывает, следует ли отображать комментарии на слайдах

```cpp
bool Aspose::Slides::Export::HandoutLayoutingOptions::get_PrintComments() const
```

## Примечания

Значение по умолчанию — **false**. 

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);
handoutLayoutingOptions->set_PrintComments(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

System::Drawing::Size size(1920, 1080);
pres->get_Slide(0)->GetThumbnail(options, size)->Save(u"pres-handout.png");
```

## Смотрите также

* Класс [HandoutLayoutingOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)