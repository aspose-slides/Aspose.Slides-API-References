---
title: CheckWriteProtection()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: กำหนดว่าการนำเสนอได้รับการป้องกันด้วยรหัสผ่านเพื่อแก้ไขหรือไม่.
type: docs
weight: 157
url: /th/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) เมธอด

กำหนดว่าการนำเสนอได้รับการป้องกันด้วยรหัสผ่านเพื่อแก้ไขหรือไม่.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | รหัสผ่านสำหรับการตรวจสอบ. |

### ค่าที่ส่งกลับ

True if the password is valid; otherwise, false.

## หมายเหตุ

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. คุณควรตรวจสอบคุณสมบัติ [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) ก่อนเรียกใช้เมธอดนี้.
1. เมื่อรหัสผ่านเป็นค่า null หรือว่างเปล่า เมธอดนี้จะคืนค่า false.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [IProtectionManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)