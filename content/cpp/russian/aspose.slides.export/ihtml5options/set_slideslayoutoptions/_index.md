---
title: set_SlidesLayoutOptions()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает режим, в котором слайды размещаются на странице при экспортировании презентации ISlidesLayoutOptions.
type: docs
weight: 144
url: /ru/aspose.slides.export/ihtml5options/set_slideslayoutoptions/
---
## IHtml5Options::set_SlidesLayoutOptions(System::SharedPtr\<ISlidesLayoutOptions\>) метод


Устанавливает режим, в котором слайды размещаются на странице при экспортировании презентации [ISlidesLayoutOptions](../../islideslayoutoptions/).

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_SlidesLayoutOptions(System::SharedPtr<ISlidesLayoutOptions> value)=0
```

## Примечания


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HandoutLayoutingOptions> slidesLayoutOptions = System::MakeObject<HandoutLayoutingOptions>();
slidesLayoutOptions->set_Handout(HandoutType::Handouts4Horizontal);

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_SlidesLayoutOptions(slidesLayoutOptions);

pres->Save(u"pres.html", SaveFormat::Html5, options);
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISlidesLayoutOptions](../../islideslayoutoptions/)
* Класс [IHtml5Options](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)