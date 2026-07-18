---
title: GetRect()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λάβετε τις συντεταγμένες του rect που περιβάλλει το τμήμα. Το rect περιλαμβάνει όλες τις γραμμές κειμένου στο τμήμα, συμπεριλαμβανομένων και των κενών.
type: docs
weight: 79
url: /el/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() μέθοδος


Λάβετε τις συντεταγμένες του rect που περιβάλλει το τμήμα. Το rect περιλαμβάνει όλες τις γραμμές κειμένου στο τμήμα, συμπεριλαμβανομένων και των κενούς.

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```


### Τιμή Επιστροφής

Rectangle that bounds portion [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)
## Σχόλια



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
* Κλάση [IPortion](../)
* Ονομαχώρος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)