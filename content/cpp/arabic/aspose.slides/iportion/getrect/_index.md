---
title: GetRect()
second_title: Aspose.Slides لـ C++ مرجع API
description: احصل على إحداثيات المستطيل الذي يحد الجزء. يتضمن المستطيل جميع أسطر النص في الجزء، بما في ذلك الفارغة.
type: docs
weight: 79
url: /ar/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() طريقة

احصل على إحداثيات المستطيل الذي يحد الجزء. يتضمن المستطيل جميع أسطر النص في الجزء، بما في ذلك الفارغ منها.

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```

### قيمة الإرجاع

Rectangle الذي يحد الجزء [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)

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
* الفئة [IPortion](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)