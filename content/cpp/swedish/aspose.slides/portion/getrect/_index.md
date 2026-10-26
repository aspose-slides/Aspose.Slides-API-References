---
title: GetRect()
second_title: Aspose.Slides för C++ API-referens
description: Hämta koordinaterna för rektangeln som avgränsar delen. Rektangeln inkluderar alla textrader i delen, inklusive tomma.
type: docs
weight: 92
url: /sv/aspose.slides/portion/getrect/
---
## Portion::GetRect() metod

Hämta koordinaterna för rect som avgränsar portion. Rect inkluderar alla rader med text i portion, inklusive tomma.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## Anmärkningar

Exempel:
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

## Se också

* Klass [RectangleF](../../../system.drawing/rectanglef/)
* Klass [Portion](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)