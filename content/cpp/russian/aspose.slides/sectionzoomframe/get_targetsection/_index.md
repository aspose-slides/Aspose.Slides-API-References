---
title: get_TargetSection()
second_title: Справочник API Aspose.Slides для C++
description: Получает объект раздела, к которому привязан объект Section Zoom. Читайте ISection.
type: docs
weight: 1
url: /ru/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() метод


Получает объект раздела, к которому привязан объект Zoom [Section](../../section/). Читайте [ISection](../../isection/).

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## Примечания


Следующий пример демонстрирует изменение целевого раздела и создание нового изображения для объекта зум-раздела: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISection](../../isection/)
* Класс [SectionZoomFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)