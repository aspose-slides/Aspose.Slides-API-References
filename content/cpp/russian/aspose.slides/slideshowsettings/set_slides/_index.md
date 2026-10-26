---
title: set_Slides()
second_title: Справочник API Aspose.Slides для C++
description: Диапазон слайдов
type: docs
weight: 131
url: /ru/aspose.slides/slideshowsettings/set_slides/
---
## SlideShowSettings::set_Slides(System::SharedPtr\<SlidesRange\>) метод


[Slides](../../) диапазон

```cpp
void Aspose::Slides::SlideShowSettings::set_Slides(System::SharedPtr<SlidesRange> value)
```

## Примечания


```cpp
auto pres = System::MakeObject<Presentation>();

auto slidesRange = System::MakeObject<SlidesRange>();
slidesRange->set_Start(1);
slidesRange->set_End(3);

pres->get_SlideShowSettings()->set_Slides(slidesRange);
```




## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [SlidesRange](../../slidesrange/)
* Класс [SlideShowSettings](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)