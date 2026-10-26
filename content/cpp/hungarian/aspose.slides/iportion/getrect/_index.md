---
title: GetRect()
second_title: Aspose.Slides a C++ API referencia
description: Lekéri a részletet körülvevő téglalap koordinátáit. A téglalap tartalmazza a részletben lévő összes szövegsort, beleértve az üres sorokat is.
type: docs
weight: 79
url: /hu/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() metódus


Lekérdezi a részletet körülvevő téglalap koordinátáit. A téglalap tartalmazza a részletben lévő összes szövegsort, beleértve az üres sorokat is.

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```


### Visszatérési érték

Téglalap, amely a részletet körülveszi [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)
## Megjegyzések



Példa: 
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

## Lásd még

* Osztály [RectangleF](../../../system.drawing/rectanglef/)
* Osztály [IPortion](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)