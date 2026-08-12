---
title: SetWriteProtection()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตั้งค่าการป้องกันการเขียนสำหรับงานนำเสนอนี้ด้วยรหัสผ่านที่ระบุ.
type: docs
weight: 131
url: /th/aspose.slides/protectionmanager/setwriteprotection/
---
## ProtectionManager::SetWriteProtection(System::String) เมธอด


ตั้งค่าการป้องกันการเขียนสำหรับงานนำเสนอนี้ด้วยรหัสผ่านที่ระบุ.

```cpp
void Aspose::Slides::ProtectionManager::SetWriteProtection(System::String password) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | รหัสผ่าน. |
## หมายเหตุ



โค้ดตัวอย่างต่อไปนี้แสดงวิธีตั้งค่าการป้องกันการเขียนให้กับงานนำเสนอ. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->SetWriteProtection(u"123123");
presentation->Save(u"write-protected-pres.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [ProtectionManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)