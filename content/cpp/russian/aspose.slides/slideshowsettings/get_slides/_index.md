---
title: get_Slides()
second_title: Справочник API Aspose.Slides для C++
description: Диапазон слайдов
type: docs
weight: 118
url: /ru/aspose.slides/slideshowsettings/get_slides/
---
## SlideShowSettings::get_Slides() const метод


[Slides](../../) диапазон

```cpp
System::SharedPtr<SlidesRange> Aspose::Slides::SlideShowSettings::get_Slides() const
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