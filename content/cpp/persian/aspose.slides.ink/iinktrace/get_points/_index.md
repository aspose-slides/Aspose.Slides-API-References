---
title: get_Points()
second_title: Aspose.Slides برای C++ مرجع API
description: "نقاط مربوط به IInkLine System::Drawing::PointF را به‌صورت فقط‌خواندنی دریافت می‌کند."
type: docs
weight: 14
url: /fa/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() متد

نقاط مربوط به IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) را به‌صورت فقط خواندنی دریافت می‌کند.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## توضیحات

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## موارد مرتبط

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [PointF](../../../system.drawing/pointf/)
* کلاس [IInkTrace](../)
* فضای‌نام [Aspose::Slides::Ink](../../)
* کتابخانه [Aspose.Slides](../../../)