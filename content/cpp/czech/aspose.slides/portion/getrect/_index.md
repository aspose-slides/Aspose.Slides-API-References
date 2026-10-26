---
title: GetRect()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá souřadnice obdélníku ohraničujícího část. Obdélník zahrnuje všechny řádky textu v části, včetně prázdných.
type: docs
weight: 92
url: /cs/aspose.slides/portion/getrect/
---
## Portion::GetRect() metoda


Získejte souřadnice obdélníku, který ohraničuje část. Obdélník zahrnuje všechny řádky textu v části, včetně prázdných.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## Poznámky


Příklad:
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

## Viz také

* Třída [RectangleF](../../../system.drawing/rectanglef/)
* Třída [Portion](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)