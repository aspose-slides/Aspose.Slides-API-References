---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: กำหนดการคงสภาพของ ActiveX control เมื่อวิธีการที่ใช้ในการคงสภาพคือ PersistStream, PersistStreamInit หรือ PersistStorage.
type: docs
weight: 118
url: /th/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() เมธอด

กำหนดการคงสภาพของ ActiveX control เมื่อวิธีการที่ใช้ในการคงสภาพคือ PersistStream, PersistStreamInit หรือ PersistStorage.

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## หมายเหตุ

ตัวอย่างต่อไปแสดงการใช้คุณสมบัติ ActiveXControlBinary สำหรับการเปลี่ยนแปลงคุณสมบัติของ ActiveX:

```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // ใช้วิธีของคุณเองสำหรับจัดการคุณสมบัติของ ActiveX ที่จัดเก็บในไฟล์ไบนารีของมัน
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../../system/arrayptr/)
* คลาส [Control](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)