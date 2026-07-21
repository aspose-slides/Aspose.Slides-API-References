---
title: set_SlideShowType()
second_title: Aspose.Slides для C++ справочник API
description: "Устанавливает тип слайд-шоу. Представлен следующими предками SlideShowType: BrowsedAtKiosk, PresentedBySpeaker и BrowsedByIndividual"
type: docs
weight: 14
url: /ru/aspose.slides/slideshowsettings/set_slideshowtype/
---
## SlideShowSettings::set_SlideShowType(System::SharedPtr\<Aspose::Slides::SlideShowType\>) метод

Устанавливает тип слайд-шоу. Представлен следующими [SlideShowType](../../slideshowtype/) предками: [BrowsedAtKiosk](../../browsedatkiosk/), [PresentedBySpeaker](../../presentedbyspeaker/) и [BrowsedByIndividual](../../browsedbyindividual/)

```cpp
void Aspose::Slides::SlideShowSettings::set_SlideShowType(System::SharedPtr<Aspose::Slides::SlideShowType> value)
```

## Примечания

```cpp
auto pres = System::MakeObject<Presentation>();

// установить тип "Просмотр в режиме киоска (полный экран)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedAtKiosk>());

// установить тип "Просмотр отдельным пользователем (окно)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<BrowsedByIndividual>());

// установить тип "Презентация спикером (полный экран)"
pres->get_SlideShowSettings()->set_SlideShowType(System::MakeObject<PresentedBySpeaker>());
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SlideShowType](../../slideshowtype/)
* Class [SlideShowSettings](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)