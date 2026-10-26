---
title: GetRect()
second_title: Aspose.Slides voor C++ API-referentie
description: Haal de coördinaten op van de rechthoek die het gedeelte begrenst. De rechthoek bevat alle tekstregels in het gedeelte, inclusief lege regels.
type: docs
weight: 92
url: /nl/aspose.slides/portion/getrect/
---
## Portion::GetRect() methode


Haal de coördinaten op van de rechthoek die het gedeelte begrenst. De rechthoek bevat alle tekstregels in het gedeelte, inclusief lege regels.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## Opmerkingen


Voorbeeld: 
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

## Zie ook

* Klasse [RectangleF](../../../system.drawing/rectanglef/)
* Klasse [Portion](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)