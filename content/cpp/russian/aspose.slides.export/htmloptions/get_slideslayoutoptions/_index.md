---
title: get_SlidesLayoutOptions()
second_title: Справочник API Aspose.Slides для C++
description: Получает режим, в котором слайды размещаются на странице при экспорте презентации ISlidesLayoutOptions.
type: docs
weight: 1
url: /ru/aspose.slides.export/htmloptions/get_slideslayoutoptions/
---
## HtmlOptions::get_SlidesLayoutOptions() метод

Получает режим, в котором слайды размещаются на странице при экспорте презентации [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::HtmlOptions::get_SlidesLayoutOptions() override
```

## Примечания

Пример:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.html", SaveFormat::Html, options);
```

## Смотрите также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Класс [HtmlOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)