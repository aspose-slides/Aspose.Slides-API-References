---
title: GetRect()
second_title: Aspose.Slides ل C++ مرجع API
description: احصل على إحداثيات المستطيل الذي يحد الجزء. المستطيل يشمل جميع أسطر النص في الجزء، بما في ذلك الأسطر الفارغة.
type: docs
weight: 92
url: /ar/aspose.slides/portion/getrect/
---
## Portion::GetRect() طريقة

احصل على إحداثيات المستطيل الذي يحد الجزء. المستطيل يشمل جميع أسطر النص في الجزء، بما في ذلك الأسطر الفارغة.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## ملاحظات

مثال:

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

## انظر أيضًا

* الفئة [RectangleF](../../../system.drawing/rectanglef/)
* الفئة [Portion](../)
* المجال [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)