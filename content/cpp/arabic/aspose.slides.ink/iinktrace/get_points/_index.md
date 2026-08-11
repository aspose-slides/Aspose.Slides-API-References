---
title: get_Points()
second_title: Aspose.Slides لـ C++ مرجع API
description: "يجلب النقاط لـ IInkLine System::Drawing::PointF للقراءة فقط."
type: docs
weight: 14
url: /ar/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() طريقة

يجلب النقاط لـ IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) للقراءة فقط.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
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
* فئة [IInkTrace](../)
* نطاق الاسم [Aspose::Slides::Ink](../../)
* مكتبة [Aspose.Slides](../../../)