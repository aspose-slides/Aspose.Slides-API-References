---
title: CheckWriteProtection()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบว่ารหัสผ่านสำหรับการแก้ไขนั้นถูกต้องสำหรับการนำเสนอที่มีการป้องกันการเขียนหรือไม่.
type: docs
weight: 66
url: /th/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) เมธอด

ตรวจสอบว่ารหัสผ่านสำหรับการแก้ไขนั้นถูกต้องสำหรับการนำเสนอที่มีการป้องกันการเขียนหรือไม่.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | รหัสผ่านที่ต้องการตรวจสอบ. |

### ค่าที่คืนกลับ

True หากการนำเสนอถูกป้องกันการเขียนและรหัสผ่านถูกต้อง. False ในกรณีอื่น.

## หมายเหตุ



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. คุณควรตรวจสอบคุณสมบัติ [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) ก่อนเรียกใช้เมธอดนี้.
1. เมื่อรหัสผ่านเป็นค่า null หรือว่างเปล่า เมธอดนี้จะคืนค่า false.

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [PresentationInfo](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)