---
title: GetRect()
second_title: Ссылка на API Aspose.Slides для C++
description: Получить координаты rect, ограничивающего portion. rect включает все строки текста в portion, включая пустые.
type: docs
weight: 92
url: /ru/aspose.slides/portion/getrect/
---
## Portion::GetRect() метод


Получить координаты rect, ограничивающего portion. rect включает все строки текста в portion, включая пустые.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

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

## Смотри также

* Класс [RectangleF](../../../system.drawing/rectanglef/)
* Класс [Portion](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)