---
title: GetRect()
second_title: Aspose.Slides برای مرجع API C++
description: مختصات مستطیلی که بخش را محدود می‌کند دریافت کنید. این مستطیل شامل تمام خطوط متن در بخش، از جمله خطوط خالی است.
type: docs
weight: 92
url: /fa/aspose.slides/portion/getrect/
---
## Portion::GetRect() متد


مختصات مستطیل محدوده بخش را دریافت می‌کند. این مستطیل شامل تمام خطوط متن در بخش، از جمله خطوط خالی است.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## توضیحات


مثال: ```cpp
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

## موارد مرتبط

* کلاس [RectangleF](../../../system.drawing/rectanglef/)
* کلاس [Portion](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)