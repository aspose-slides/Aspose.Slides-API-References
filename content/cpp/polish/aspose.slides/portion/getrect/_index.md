---
title: GetRect()
second_title: Aspose.Slides – odniesienie API dla C++
description: Pobierz współrzędne prostokąta ograniczającego fragment. Prostokąt zawiera wszystkie linie tekstu w fragmencie, w tym puste.
type: docs
weight: 92
url: /pl/aspose.slides/portion/getrect/
---
## Portion::GetRect() metoda


Pobierz współrzędne prostokąta ograniczającego fragment. Prostokąt zawiera wszystkie linie tekstu w fragmencie, w tym puste.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## Uwagi


Przykład:
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

## Zobacz także

* Klasa [RectangleF](../../../system.drawing/rectanglef/)
* Klasa [Portion](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)