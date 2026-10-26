---
title: GetRect()
second_title: Aspose.Slides för C++ API-referens
description: Hämta koordinaterna för den rektangel som avgränsar delen. Rektangeln inkluderar alla textrader i delen, inklusive tomma.
type: docs
weight: 79
url: /sv/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() metod

Hämta koordinaterna för den rektangel som avgränsar delen. Rektangeln inkluderar alla textrader i delen, inklusive tomma.

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```

### Returvärde

Rectangle that bounds portion [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)
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

## Se även

* Klass [RectangleF](../../../system.drawing/rectanglef/)
* Klass [IPortion](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)