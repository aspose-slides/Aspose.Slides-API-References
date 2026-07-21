---
title: set_SlidesLayoutOptions()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает режим, в котором слайды размещаются на странице при экспорте презентации ISlidesLayoutOptions.
type: docs
weight: 14
url: /ru/aspose.slides.export/renderingoptions/set_slideslayoutoptions/
---
## RenderingOptions::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) метод


Устанавливает режим, в котором слайды размещаются на странице при экспорте презентации [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
void Aspose::Slides::Export::RenderingOptions::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value) override
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);
slidesLayoutOptions->set_PrintSlideNumbers(false);

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

System::ArrayPtr<System::SharedPtr<System::Drawing::Bitmap>> handoutSlides = pres->GetThumbnails(options);
for (int32_t index = 0; index < handoutSlides->get_Length(); index++)
{
    auto handoutSlide = handoutSlides[index];
    handoutSlide->Save(System::String::Format(u"handout-{0}.png", index));
}
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Класс [RenderingOptions](../)
* Пространство имен [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)