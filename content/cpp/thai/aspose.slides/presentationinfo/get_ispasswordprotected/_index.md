---
title: get_IsPasswordProtected()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับค่าที่บ่งชี้ว่าการนำเสนอที่เชื่อมโยงถูกปกป้องด้วยรหัสผ่านเพื่อเปิดหรือไม่.
type: docs
weight: 14
url: /th/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() เมธอด

รับค่าที่บ่งชี้ว่าการนำเสนอที่เชื่อมโยงถูกปกป้องด้วยรหัสผ่านเพื่อเปิดหรือไม่.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## หมายเหตุ



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## ดูเพิ่มเติม

* คลาส [PresentationInfo](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)