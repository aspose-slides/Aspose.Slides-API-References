---
title: CheckWriteProtection()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตรวจสอบว่ารหัสผ่านสำหรับการแก้ไขนั้นถูกต้องสำหรับงานนำเสนอที่มีการป้องกันการเขียนหรือไม่.
type: docs
weight: 66
url: /th/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) เมธอด


ตรวจสอบว่ารหัสผ่านสำหรับการแก้ไขถูกต้องสำหรับงานนำเสนอที่มีการป้องกันการเขียนหรือไม่.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | รหัสผ่านที่ต้องตรวจสอบ. |

### ค่าที่ส่งกลับ

True หากงานนำเสนอถูกป้องกันการเขียนและรหัสผ่านถูกต้อง. False หากไม่เป็นเช่นนั้น.
## หมายเหตุ



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. คุณควรตรวจสอบคุณสมบัติ [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) ก่อนเรียกเมธอดนี้.
1. เมื่อรหัสผ่านเป็นค่า null หรือว่างเปล่า เมธอดนี้จะคืนค่า false.



## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [IPresentationInfo](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)