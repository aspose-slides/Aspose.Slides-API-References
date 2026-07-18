---
title: GetRect()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λάβετε τις συντεταγμένες του ορθογωνίου που περιορίζει το τμήμα. Το ορθογώνιο περιλαμβάνει όλες τις γραμμές κειμένου στο τμήμα, συμπεριλαμβανομένων και των κενών.
type: docs
weight: 92
url: /el/aspose.slides/portion/getrect/
---
## Portion::GetRect() μέθοδος


Λάβετε τις συντεταγμένες του ορθογωνίου που περιορίζει το τμήμα. Το ορθογώνιο περιλαμβάνει όλες τις γραμμές κειμένου στο τμήμα, συμπεριλαμβανομένων και των κενών.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## Παρατηρήσεις


Παράδειγμα: 
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

## Δείτε επίσης

* Κλάση [RectangleF](../../../system.drawing/rectanglef/)
* Κλάση [Portion](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)