---
title: get_GridSpacing()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ส่งคืนค่าความห่างของกริดที่ควรใช้สำหรับกริดที่เป็นพื้นฐานของเอกสารการนำเสนอ โดยหน่วยเป็นจุด อ่าน float.
type: docs
weight: 92
url: /th/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() วิธีการ


ส่งคืนค่าความห่างของกริดที่ควรใช้สำหรับกริดที่เป็นพื้นฐานของเอกสารการนำเสนอ โดยหน่วยเป็นจุด อ่าน **float**.

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
```

## หมายเหตุ


ค่าความห่างของกริดต้องเป็นจำนวนบวก ช่วงค่าที่ทั่วไปอยู่ระหว่าง 1 มม. (2.8349607 จุด) ถึง 2 นิ้ว (144 จุด). 

ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการเปลี่ยนความห่างของกริดในงานนำเสนอ PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [IViewProperties](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)