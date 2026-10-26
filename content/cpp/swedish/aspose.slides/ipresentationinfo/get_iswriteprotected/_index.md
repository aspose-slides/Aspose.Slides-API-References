---
title: get_IsWriteProtected()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar ett värde som indikerar om en bunden presentation är skrivskyddad.
type: docs
weight: 27
url: /sv/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() method


Hämtar ett värde som indikerar om en bunden presentation är skrivskyddad.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## Anmärkningar



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Om presentationen är skyddad med ett lösenord för att öppna, är egenskapsvärdet lika med NotDefined. Se [NullableBool](../../nullablebool/)-enumerationen. 
## Se även

* Enum [NullableBool](../../nullablebool/)
* Klass [IPresentationInfo](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)