---
title: CheckPassword()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตรวจสอบว่ารหัสผ่านถูกต้องสำหรับงานนำเสนอที่ได้รับการป้องกันด้วยรหัสผ่านเปิดหรือไม่
type: docs
weight: 53
url: /th/aspose.slides/ipresentationinfo/checkpassword/
---
## IPresentationInfo::CheckPassword(System::String) เมธอด

ตรวจสอบว่ารหัสผ่านถูกต้องสำหรับงานนำเสนอที่ได้รับการป้องกันด้วยรหัสผ่านเปิดหรือไม่

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckPassword(System::String password)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | รหัสผ่านที่จะตรวจสอบ |

### ค่าที่ส่งกลับ

True หากงานนำเสนอได้รับการป้องกันด้วยรหัสผ่านเปิดและรหัสผ่านถูกต้องและ false ในกรณีอื่น

## หมายเหตุ

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```

เมื่อรหัสผ่านเป็นค่า null หรือว่างเปล่า เมธอดนี้จะคืนค่า false

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [IPresentationInfo](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)