---
title: GetRect()
second_title: Aspose.Slides برای C++ مرجع API
description: مختصات مستطیلی که بخش را محصور می‌کند دریافت می‌کند. این مستطیل شامل تمام خطوط متن در بخش است، از جمله خطوط خالی.
type: docs
weight: 79
url: /fa/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() متد


مختصات مستطیلی که بخش را محصور می‌کند دریافت می‌کند. این مستطیل شامل تمام خطوط متن در بخش است، از جمله خطوط خالی.

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```


### مقدار بازگشت

مستطیل که بخش را محصور می‌کند [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)
## توضیحات



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

## موارد مرتبط

* کلاس [RectangleF](../../../system.drawing/rectanglef/)
* کلاس [IPortion](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)