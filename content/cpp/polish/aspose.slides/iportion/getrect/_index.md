---
title: GetRect()
second_title: Odwołanie API Aspose.Slides dla C++
description: Pobierz współrzędne prostokąta, który ogranicza fragment. Prostokąt obejmuje wszystkie linie tekstu w fragmencie, w tym puste.
type: docs
weight: 79
url: /pl/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() metoda


Pobierz współrzędne prostokąta, który ogranicza fragment. Prostokąt obejmuje wszystkie linie tekstu w fragmencie, w tym puste.

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```


### Wartość zwracana

Prostokąt, który ogranicza fragment [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)
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
* Klasa [IPortion](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)