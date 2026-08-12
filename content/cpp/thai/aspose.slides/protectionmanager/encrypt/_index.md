---
title: Encrypt()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: เข้ารหัส Presentation ด้วยรหัสผ่านที่ระบุ.
type: docs
weight: 105
url: /th/aspose.slides/protectionmanager/encrypt/
---
## ProtectionManager::Encrypt(System::String) เมธอด

เข้ารหัส [Presentation](../../presentation/) ด้วยรหัสผ่านที่ระบุ.

```cpp
void Aspose::Slides::ProtectionManager::Encrypt(System::String encryptionPassword) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| encryptionPassword | [System::String](../../../system/string/) | รหัสผ่าน. |
## หมายเหตุ



ตัวอย่างโค้ดต่อไปนี้แสดงวิธีการเข้ารหัส PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"pres.pptx");
presentation->get_ProtectionManager()->Encrypt(u"123123");
presentation->Save(u"encrypted-pres.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [ProtectionManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)