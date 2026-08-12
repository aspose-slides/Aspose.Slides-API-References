---
title: CheckWriteProtection()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ระบุว่าการนำเสนอได้รับการป้องกันด้วยรหัสผ่านเพื่อแก้ไขหรือไม่.
type: docs
weight: 157
url: /th/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) เมธอด


กำหนดว่าการนำเสนอถูกป้องกันด้วยรหัสผ่านเพื่อทำการแก้ไขหรือไม่

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | รหัสผ่านสำหรับการตรวจสอบ. |

### ค่าที่ส่งคืน

True หากรหัสผ่านถูกต้อง; มิฉะนั้น, false.
## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. คุณควรตรวจสอบคุณสมบัติ [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) ก่อนเรียกใช้เมธอดนี้.
1. เมื่อรหัสผ่านเป็น null หรือว่างเปล่า เมธอดนี้จะคืนค่า false.


## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [ProtectionManager](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)