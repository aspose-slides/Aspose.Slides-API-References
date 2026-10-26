---
title: get_IsWriteProtected()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar ett värde som anger om en bunden presentation är skrivskyddad.
type: docs
weight: 27
url: /sv/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() metod


Hämtar ett värde som anger om en bunden presentation är skrivskyddad.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## Anmärkningar



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Om presentationen är skyddad med ett lösenord för öppning, är egenskapsvärdet lika med NotDefined. 
## Se även

* Enum [NullableBool](../../nullablebool/)
* Klass [PresentationInfo](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)