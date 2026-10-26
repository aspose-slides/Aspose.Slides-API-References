---
title: GetRect()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt die Koordinaten des Rechtecks, das den Abschnitt begrenzt. Das Rechteck umfasst alle Textzeilen im Abschnitt, einschließlich leerer Zeilen.
type: docs
weight: 92
url: /de/aspose.slides/portion/getrect/
---
## Portion::GetRect() Methode

Ermittelt die Koordinaten des Rechtecks, das den Abschnitt begrenzt. Das Rechteck umfasst alle Textzeilen im Abschnitt, einschließlich leerer Zeilen.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## Bemerkungen

Beispiel:
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

## Siehe auch

* Klasse [RectangleF](../../../system.drawing/rectanglef/)
* Klasse [Portion](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)