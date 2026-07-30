---
title: GetRect()
second_title: Riferimento API Aspose.Slides per C++
description: Ottieni le coordinate del rect che delimita la porzione. Il rect include tutte le righe di testo nella porzione, incluse quelle vuote.
type: docs
weight: 92
url: /it/aspose.slides/portion/getrect/
---
## Portion::GetRect() metodo

Ottieni le coordinate del rect che delimita la porzione. Il rect include tutte le righe di testo nella porzione, incluse quelle vuote.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## Osservazioni

Esempio: 
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

## Vedi anche

* Classe [RectangleF](../../../system.drawing/rectanglef/)
* Classe [Portion](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)