---
title: set_GridSpacing()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает интервал сетки, который должен использоваться для сетки, лежащей в основе презентационного документа, в пунктах. Запишите float.
type: docs
weight: 105
url: /ru/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) метод

Устанавливает интервал сетки, который должен использоваться для сетки, лежащей в основе презентационного документа, в пунктах. Запишите **float**.

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## Примечания

Значение интервала сетки должно быть положительным числом. Обычный диапазон значений — от 1 mm (2.8349607 points) до 2 inches (144 points).

Следующий пример кода показывает, как изменить интервал сетки в презентации PowerPoint.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [IViewProperties](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)