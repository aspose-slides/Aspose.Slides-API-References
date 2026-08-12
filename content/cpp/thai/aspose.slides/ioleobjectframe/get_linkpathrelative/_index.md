---
title: get_LinkPathRelative()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "คืนค่าเส้นทางสัมพันธ์ไปยังไฟล์ที่เชื่อมโยงหากมี, มิฉะนั้นจะคืนสตริงว่าง. อ่านอย่างเดียว System::String."
type: docs
weight: 118
url: /th/aspose.slides/ioleobjectframe/get_linkpathrelative/
---
## IOleObjectFrame::get_LinkPathRelative() เมธอด

คืนค่าเส้นทางสัมพันธ์ไปยังไฟล์ที่เชื่อมโยงหากมี, มิฉะนั้นจะคืนสตริงว่าง. อ่านอย่างเดียว [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::IOleObjectFrame::get_LinkPathRelative()=0
```

## หมายเหตุ

ในงานนำเสนอ PPT, ลิงก์วัตถุ Ole บางอย่างอาจมีการแสดงผลแบบสัมพันธ์.

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.ppt");

auto oleFrame = System::AsCast<Aspose::Slides::IOleObjectFrame>(presentation->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));

if (oleFrame != nullptr)
{
    System::Console::WriteLine(System::String(u"The relative path: ") + oleFrame->get_LinkPathRelative());
}
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [IOleObjectFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)