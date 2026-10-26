---
title: get_SlideShowType()
second_title: Aspose.Slides для C++ справка по API
description: "Получает тип слайд-шоу. Представлен следующими предками SlideShowType: BrowsedAtKiosk, PresentedBySpeaker и BrowsedByIndividual"
type: docs
weight: 1
url: /ru/aspose.slides/slideshowsettings/get_slideshowtype/
---
## SlideShowSettings::get_SlideShowType() метод

Получает тип слайд-шоу. Представлен следующими [SlideShowType](../../slideshowtype/) предками: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) и [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
System::SharedPtr<Aspose::Slides::SlideShowType> Aspose::Slides::SlideShowSettings::get_SlideShowType()
```

## Примечания

```cpp
auto pres = System::MakeObject<Presentation>();

// установить тип "Просмотр в режиме киоска (полный экран)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// установить тип "Просмотр индивидуальный (окно)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// установить тип "Представление спикером (полный экран)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [SlideShowType](../../slideshowtype/)
* Класс [SlideShowSettings](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)