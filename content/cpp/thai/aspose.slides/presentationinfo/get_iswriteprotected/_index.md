---
title: get_IsWriteProtected()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับค่าที่บ่งชี้ว่าการนำเสนอที่ผูกไว้ถูกป้องกันการเขียนหรือไม่
type: docs
weight: 27
url: /th/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() เมธอด


รับค่าที่บ่งชี้ว่าการนำเสนอที่ผูกไว้ถูกป้องกันการเขียนหรือไม่

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## หมายเหตุ



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


หากการนำเสนอถูกป้องกันด้วยรหัสผ่านเพื่อเปิด ค่าของพรอพเพอร์ตี้จะเท่ากับ NotDefined. 
## ดูเพิ่มเติม

* Enum [NullableBool](../../nullablebool/)
* คลาส [PresentationInfo](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)