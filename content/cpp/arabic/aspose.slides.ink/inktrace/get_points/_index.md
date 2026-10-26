---
title: get_Points()
second_title: Aspose.Slides ل C++ مرجع API
description: "يحصل على النقاط لخط IInkLine System::Drawing::PointF قراءة فقط."
type: docs
weight: 14
url: /ar/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() طريقة


يحصل على النقاط لخط IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) قراءة فقط.

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
```

## ملاحظات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [PointF](../../../system.drawing/pointf/)
* فئة [InkTrace](../)
* فضاء أسماء [Aspose::Slides::Ink](../../)
* مكتبة [Aspose.Slides](../../../)