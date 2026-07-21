---
title: set_GridSpacing()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает интервал сетки, который должен использоваться для сетки, лежащей в основе презентационного документа, в пунктах. Запишите float.
type: docs
weight: 105
url: /ru/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) метод

Устанавливает интервал сетки, который должен использоваться для сетки, лежащей в основе презентационного документа, в пунктах. Запишите **float**.

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## Примечания

Значение интервала сетки должно быть положительным числом. Типичный диапазон значений — от 1 мм (2.8349607 пункта) до 2 дюймов (144 пункта).

Следующий пример кода показывает, как изменить интервал сетки в презентации PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Класс [ViewProperties](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)