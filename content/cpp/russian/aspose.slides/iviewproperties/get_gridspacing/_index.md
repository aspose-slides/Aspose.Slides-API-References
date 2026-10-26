---
title: get_GridSpacing()
second_title: Aspose.Slides для C++ справка API
description: Возвращает интервал сетки, который следует использовать для сетки, лежащей в основе презентационного документа, в пунктах. Только для чтения float.
type: docs
weight: 92
url: /ru/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() метод


Возвращает значение интервала сетки, которое следует использовать для сетки, лежащей в основе презентационного документа, в пунктах. Только для чтения **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## Примечания


Значение интервала сетки должно быть положительным числом. Обычный диапазон значений находится от 1 мм (2.8349607 пунктов) до 2 дюймов (144 пунктов). 

Приведённый ниже пример кода показывает, как изменить интервал сетки в презентации PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## См. также

* Класс [IViewProperties](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)