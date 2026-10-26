---
title: get_LinkPathRelative()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "ส่งคืนเส้นทางสัมพัทธ์ไปยังไฟล์ที่เชื่อมโยงหากมีอยู่ ไม่เช่นนั้นจะส่งคืนสตริงว่าง อ่านอย่างเดียว System::String."
type: docs
weight: 131
url: /th/aspose.slides/oleobjectframe/get_linkpathrelative/
---
## OleObjectFrame::get_LinkPathRelative() เมธอด

ส่งคืนเส้นทางสัมพัทธ์ไปยังไฟล์ที่เชื่อมโยงหากมีอยู่ ไม่เช่นนั้นจะส่งคืนสตริงว่าง อ่านอย่างเดียว [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::OleObjectFrame::get_LinkPathRelative() override
```

## หมายเหตุ

ในการนำเสนอ Ppt บางลิงก์วัตถุ Ole อาจมีการแสดงแบบสัมพัทธ์. 

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
* คลาส [OleObjectFrame](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)