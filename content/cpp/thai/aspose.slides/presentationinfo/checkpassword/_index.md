---
title: CheckPassword()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ตรวจสอบว่ารหัสผ่านถูกต้องสำหรับงานนำเสนอที่ได้รับการปกป้องด้วยรหัสผ่านเปิดหรือไม่.
type: docs
weight: 53
url: /th/aspose.slides/presentationinfo/checkpassword/
---
## PresentationInfo::CheckPassword(System::String) เมธอด


ตรวจสอบว่ารหัสผ่านถูกต้องสำหรับงานนำเสนอที่ได้รับการปกป้องด้วยรหัสผ่านเปิดหรือไม่.

```cpp
bool Aspose::Slides::PresentationInfo::CheckPassword(System::String password) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | รหัสผ่านที่จะตรวจสอบ. |

### ค่าที่ส่งกลับ

True หากงานนำเสนอได้รับการปกป้องด้วยรหัสผ่านเปิดและรหัสผ่านถูกต้อง และ false ในกรณีอื่น.
## หมายเหตุ



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(u"pres.pptx");
bool isPasswordCorrect = info->CheckPassword(u"my_password");
```



เมื่อรหัสผ่านเป็นค่า null หรือว่างเปล่า เมธอดนี้จะคืนค่า false. 

## ดูเพิ่มเติม

* คลาส [String](../../../system/string/)
* คลาส [PresentationInfo](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)