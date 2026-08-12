---
title: get_Points()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "รับจุดสำหรับ IInkLine System::Drawing::PointF แบบอ่านอย่างเดียว."
type: docs
weight: 14
url: /th/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() เมธอด

รับจุดสำหรับ IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) แบบอ่านอย่างเดียว.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## หมายเหตุ

ตัวอย่าง:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## ดูเพิ่มเติม

* การกำหนดประเภท [ArrayPtr](../../../system/arrayptr/)
* คลาส [PointF](../../../system.drawing/pointf/)
* คลาส [IInkTrace](../)
* เนมสเปซ [Aspose::Slides::Ink](../../)
* ไลบรารี [Aspose.Slides](../../../)