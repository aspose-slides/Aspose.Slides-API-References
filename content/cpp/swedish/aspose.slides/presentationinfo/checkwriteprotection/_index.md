---
title: CheckWriteProtection()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om ett lösenord för att ändra är korrekt för en skrivskyddad presentation.
type: docs
weight: 66
url: /sv/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) metod


Kontrollerar om ett lösenord för att ändra är korrekt för en skrivskyddad presentation.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Lösenordet att kontrollera. |

### Returvärde

Sant om presentationen är skrivskyddad och lösenordet är korrekt. Falskt annars.
## Anmärkningar



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. Du bör kontrollera egenskapen [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) innan du anropar den här metoden.
1. När lösenordet är null eller tomt, returnerar den här metoden falskt.



## Se också

* Klass [String](../../../system/string/)
* Klass [PresentationInfo](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)