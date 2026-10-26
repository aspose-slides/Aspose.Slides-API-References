---
title: Collect
second_title: Справочник API Aspose.Slides для C++
description: Представляет группу методов, предназначенных для сбора объектов модели разных типов из Presentation.
type: docs
weight: 1
url: /ru/aspose.slides.lowcode/collect/
---
## Collect класс

Represents a group of methods intended to collect model objects of different types from [Presentation](../../aspose.slides/presentation/).

```cpp
class Collect
```

## Методы

| Метод | Описание |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Собирает все экземпляры [Shape](../../aspose.slides/shape/) в [Presentation](../../aspose.slides/presentation/). |

## Примечания



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... изменить форматирование формы или другие свойства
}
```

## См. также

* Пространство имён [Aspose::Slides::LowCode](../)
* Библиотека [Aspose.Slides](../../)