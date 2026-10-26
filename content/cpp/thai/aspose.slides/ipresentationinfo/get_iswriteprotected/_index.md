---
title: get_IsWriteProtected()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับค่าที่บ่งชี้ว่าการนำเสนอที่ผูกไว้ได้รับการป้องกันการเขียนหรือไม่
type: docs
weight: 27
url: /th/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() เมธอด

รับค่าที่บ่งชี้ว่าการนำเสนอที่ผูกไว้ได้รับการป้องกันการเขียนหรือไม่

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## หมายเหตุ

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```

หากการนำเสนอถูกป้องกันด้วยรหัสผ่านในการเปิด ค่า property จะเท่ากับ NotDefined. ดูการกำหนดค่า [NullableBool](../../nullablebool/)

## ดูเพิ่มเติม

* Enum [NullableBool](../../nullablebool/)
* Class [IPresentationInfo](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)