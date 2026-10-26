---
title: GetRect()
second_title: Aspose.Slides C++ API Referenciája
description: Lekéri a részt határoló téglalap koordinátáit. A téglalap tartalmazza a részben lévő összes szövegsort, beleértve az üres sorokat is.
type: docs
weight: 92
url: /hu/aspose.slides/portion/getrect/
---
## Portion::GetRect() metódus


Lekéri a rész határoló téglalapjának koordinátáit. A téglalap tartalmazza a részben lévő összes szövegsort, beleértve az üres sorokat is.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

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
* Osztály [Portion](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)