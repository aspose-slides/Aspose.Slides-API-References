---
title: get_SlidesLayoutOptions()
second_title: Aspose.Slides для C++ справка по API
description: Получает режим, в котором слайды размещаются на странице при экспорте презентации ISlidesLayoutOptions.
type: docs
weight: 131
url: /ru/aspose.slides.export/html5options/get_slideslayoutoptions/
---
## Html5Options::get_SlidesLayoutOptions() метод

Получает режим, в котором слайды размещаются на странице при экспорте презентации [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
System::SharedPtr<ISlidesLayoutOptions> Aspose::Slides::Export::Html5Options::get_SlidesLayoutOptions() override
```

## Примечания

Пример: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Class [Html5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)