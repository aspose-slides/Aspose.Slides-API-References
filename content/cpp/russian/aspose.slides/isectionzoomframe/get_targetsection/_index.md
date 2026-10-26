---
title: get_TargetSection()
second_title: Aspose.Slides для C++ справочник API
description: Получает объект раздела, к которому привязан объект Section Zoom. Читайте ISection.
type: docs
weight: 1
url: /ru/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() метод


Получает объект раздела, к которому привязан объект [Section](../../section/) Zoom. Читайте [ISection](../../isection/).

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## Примечания


Этот пример демонстрирует изменение целевого раздела и создает новое изображение для объекта масштабирования раздела: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## См. также

* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISection](../../isection/)
* Класс [ISectionZoomFrame](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)