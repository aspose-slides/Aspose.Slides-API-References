---
title: GetRect()
second_title: Aspose.Slides для C++ справочник API
description: Получить координаты прямоугольника, ограничивающего часть. Прямоугольник включает все строки текста в части, включая пустые.
type: docs
weight: 79
url: /ru/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() метод


Получите координаты прямоугольника, который ограничивает часть. Прямоугольник включает все строки текста в части, включая пустые.

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```


### Возвращаемое значение

Rectangle that bounds portion [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)
## Примечания



Пример: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::Rectangle, 50.0f, 50.0f, 200.0f, 50.0f);

shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Clear();
auto portion0 = System::MakeObject<Portion>(u"Some text");
auto portion1 = System::MakeObject<Portion>(u"GetRect text");

shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion0);
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion1);

auto rect = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(1)->GetRect();
// ...
```

## См. также

* Класс [RectangleF](../../../system.drawing/rectanglef/)
* Класс [IPortion](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)