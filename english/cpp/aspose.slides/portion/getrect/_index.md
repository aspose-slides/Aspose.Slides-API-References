---
title: GetRect()
second_title: Aspose.Slides for C++ API Reference
description: Get coordinates of rect that bounds portion. The rect includes all the lines of text in portion, including empty ones.
type: docs
weight: 92
url: /cpp/aspose.slides/portion/getrect/
---
## Portion::GetRect() method


Get coordinates of rect that bounds portion. The rect includes all the lines of text in portion, including empty ones.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## Remarks


Example: 
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

## See Also

* Class [RectangleF](../../../system.drawing/rectanglef/)
* Class [Portion](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)