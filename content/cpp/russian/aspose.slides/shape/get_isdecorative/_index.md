---
title: get_IsDecorative()
second_title: Справочник API Aspose.Slides для C++
description: Получает параметр 'Mark as decorative' чтение/запись bool.
type: docs
weight: 521
url: /ru/aspose.slides/shape/get_isdecorative/
---
## Shape::get_IsDecorative() метод


Получает параметр 'Mark as decorative' чтение/запись **bool**.

```cpp
bool Aspose::Slides::Shape::get_IsDecorative() override
```

## Примечания



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## См. также

* Класс [Shape](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)