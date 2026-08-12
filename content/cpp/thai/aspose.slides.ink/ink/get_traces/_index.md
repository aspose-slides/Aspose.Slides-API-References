---
title: get_Traces()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ดึงข้อมูล trace ทั้งหมดที่อยู่ในองค์ประกอบ IInk IInkTrace. สามารถอ่านได้เท่านั้น.
type: docs
weight: 1
url: /th/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() เมธอด

ดึงข้อมูล trace ทั้งหมดที่อยู่ในองค์ประกอบ [IInk](../../iink/) [IInkTrace](../../iinktrace/). อ่านได้อย่างเดียว.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
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
* คลาส [Ink](../)
* เนมสเปซ [Aspose::Slides::Ink](../../)
* ไลบรารี [Aspose.Slides](../../../)