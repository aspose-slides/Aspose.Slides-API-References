---
title: get_Brush()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: รับ Brush สำหรับ IInkLine IInkBrush แบบอ่านอย่างเดียว.
type: docs
weight: 1
url: /th/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() เมธอด


รับ Brush สำหรับ IInkLine [IInkBrush](../../iinkbrush/) แบบอ่านอย่างเดียว.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IInkBrush](../../iinkbrush/)
* คลาส [IInkTrace](../)
* เนมสเปซ [Aspose::Slides::Ink](../../)
* ไลบรารี [Aspose.Slides](../../../)