---
title: get_Persistence()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: รับวิธีการที่ใช้ในการเก็บคุณสมบัติของคอนโทรล ActiveX. อ่านอย่างเดียว PersistenceType.
type: docs
weight: 1
url: /th/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() เมธอด

รับวิธีการที่ใช้ในการเก็บคุณสมบัติของคอนโทรล ActiveX. อ่านอย่างเดียว [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## หมายเหตุ

ตัวอย่างต่อไปแสดงการใช้คุณสมบัติ Persistence เพื่อการตรวจสอบว่าคุณสมบัติของวัตถุ ActiveX สามารถเปลี่ยนแปลงได้เป็นคุณสมบัติของ ActiveX ที่อิงตาม XML หรือไม่: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // ใช้วิธีของคุณเองสำหรับจัดการคุณสมบัติ ActiveX ที่เก็บไว้ในไฟล์ไบนารีของมัน
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## ดูเพิ่มเติม

* Enum [PersistenceType](../../persistencetype/)
* คลาส [Control](../)
* เนมสเปซ [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)