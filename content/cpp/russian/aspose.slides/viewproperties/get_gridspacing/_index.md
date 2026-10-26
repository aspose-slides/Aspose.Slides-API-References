---
title: get_GridSpacing()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает расстояние между линиями сетки, которое следует использовать для сетки, лежащей в основе документа презентации, в пунктах. Чтение float.
type: docs
weight: 92
url: /ru/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() метод

Возвращает расстояние между линиями сетки, которое следует использовать для сетки, лежащей в основе документа презентации, в пунктах. Чтение **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## Примечания

Значение расстояния между линиями сетки должно быть положительным числом. Типичный диапазон значений от 1 мм (2.8349607 пунктов) до 2 дюймов (144 пунктов).

Следующий пример кода показывает, как изменить расстояние между линиями сетки в презентации PowerPoint.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [ViewProperties](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)