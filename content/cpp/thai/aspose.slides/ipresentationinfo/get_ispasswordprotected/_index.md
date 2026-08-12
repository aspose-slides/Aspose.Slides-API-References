---
title: get_IsPasswordProtected()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับค่าที่บ่งชี้ว่าการนำเสนอที่เชื่อมโยงถูกป้องกันด้วยรหัสผ่านสำหรับการเปิดหรือไม่
type: docs
weight: 14
url: /th/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() เมธอด

รับค่าที่ระบุว่าการนำเสนอที่เชื่อมโยงถูกป้องกันด้วยรหัสผ่านสำหรับการเปิดหรือไม่。

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## หมายเหตุ



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## ดูเพิ่มเติม

* คลาส [IPresentationInfo](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)