---
title: get_Brush()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: รับ Brush สำหรับ IInkLine IInkBrush อ่านอย่างเดียว.
type: docs
weight: 1
url: /th/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() เมธอด


รับ Brush สำหรับ IInkLine [IInkBrush](../../iinkbrush/) อ่านอย่างเดียว.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
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

* กำหนดประเภท [SharedPtr](../../../system/sharedptr/)
* คลาส [IInkBrush](../../iinkbrush/)
* คลาส [InkTrace](../)
* เนมสเปซ [Aspose::Slides::Ink](../../)
* ไลบรารี [Aspose.Slides](../../../)