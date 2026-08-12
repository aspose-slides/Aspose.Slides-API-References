---
title: get_GridSpacing()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คืนค่าการเว้นระยะของกริดที่ควรใช้สำหรับกริดพื้นฐานของเอกสารการนำเสนอ หน่วยเป็นจุด อ่าน float.
type: docs
weight: 92
url: /th/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() เมธอด

คืนค่าการเว้นระยะของกริดที่ควรใช้สำหรับกริดพื้นฐานของเอกสารการนำเสนอ หน่วยเป็นจุด. อ่าน **float**.

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## หมายเหตุ

ค่าการเว้นระยะของกริดต้องเป็นเลขจำนวนบวก. ช่วงค่าที่ทั่วไปอยู่ระหว่าง 1 มิลลิเมตร (2.8349607 จุด) ถึง 2 นิ้ว (144 จุด). 

โค้ดตัวอย่างต่อไปนี้แสดงวิธีการเปลี่ยนระยะห่างของกริดในงานนำเสนอ PowerPoint. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [ViewProperties](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)