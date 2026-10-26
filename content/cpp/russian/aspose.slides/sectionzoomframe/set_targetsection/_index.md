---
title: set_TargetSection()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает объект раздела, к которому привязан объект Section Zoom. Запишите ISection.
type: docs
weight: 14
url: /ru/aspose.slides/sectionzoomframe/set_targetsection/
---
## SectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) метод

Устанавливает объект раздела, к которому привязан объект [Section](../../section/) Zoom. Запишите [ISection](../../isection/).

```cpp
void Aspose::Slides::SectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value) override
```

## Примечания

Следующий пример демонстрирует изменение целевого раздела и создает новое изображение для объекта section zoom object: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISection](../../isection/)
* Класс [SectionZoomFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)