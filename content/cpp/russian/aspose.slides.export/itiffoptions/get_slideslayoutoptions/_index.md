---
title: get_SlidesLayoutOptions()
second_title: Справочник API Aspose.Slides для C++
description: Получает режим, в котором слайды размещаются на странице при экспорте презентации ISlidesLayoutOptions.
type: docs
weight: 157
url: /ru/aspose.slides.export/itiffoptions/get_slideslayoutoptions/
---
## ITiffOptions::get_SlidesLayoutOptions() метод


Получает режим, в котором слайды размещаются на странице при экспорте презентации [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::ITiffOptions::get_SlidesLayoutOptions()=0
```

## Примечания


Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> handoutLayoutingOptions = System::MakeObject<HandoutLayoutingOptions>();
handoutLayoutingOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_SlidesLayoutOptions(handoutLayoutingOptions);

pres->Save(u"pres.tiff", SaveFormat::Tiff, options);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Класс [ITiffOptions](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)