---
title: get_Points()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "รับจุดสำหรับ IInkLine System::Drawing::PointF แบบอ่านอย่างเดียว."
type: docs
weight: 14
url: /th/aspose.slides.ink/inktrace/get_points/
---
## InkTrace::get_Points() เมธอด


รับจุดสำหรับ IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) อ่านอย่างเดียว.

```cpp
System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::InkTrace::get_Points() override
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

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [PointF](../../../system.drawing/pointf/)
* คลาส [InkTrace](../)
* เนมสเปซ [Aspose::Slides::Ink](../../)
* ไลบรารี [Aspose.Slides](../../../)