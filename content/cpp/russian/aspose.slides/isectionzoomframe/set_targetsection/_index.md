---
title: set_TargetSection()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает объект раздела, к которому привязан объект Section Zoom. Запишите ISection.
type: docs
weight: 14
url: /ru/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) Метод


Устанавливает объект раздела, к которому привязан объект Zoom [Section](../../section/). Запишите [ISection](../../isection/).

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## Примечания


В этом примере демонстрируется изменение целевого раздела и создание нового изображения для объекта масштабирования раздела: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISection](../../isection/)
* Класс [ISectionZoomFrame](../)
* Пространство имен [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)