---
title: get_Traces()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับ trace ทั้งหมดที่อยู่ในองค์ประกอบ IInk element IInkTrace. อ่านอย่างเดียว.
type: docs
weight: 1
url: /th/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() เมธอด

รับ trace ทั้งหมดที่อยู่ในองค์ประกอบ [IInk](../) [IInkTrace](../../iinktrace/). อ่านอย่างเดียว.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## หมายเหตุ

ตัวอย่าง: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IInkTrace](../../iinktrace/)
* คลาส [IInk](../)
* เนมสเปซ [Aspose::Slides::Ink](../../)
* ไลบรารี [Aspose.Slides](../../../)