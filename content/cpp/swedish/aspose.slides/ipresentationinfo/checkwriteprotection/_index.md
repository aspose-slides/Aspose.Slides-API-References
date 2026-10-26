---
title: CheckWriteProtection()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar om ett lösenord för att ändra är korrekt för en skrivskyddad presentation.
type: docs
weight: 66
url: /sv/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) metod

Kontrollerar om ett lösenord för att ändra är korrekt för en skrivskyddad presentation.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Lösenordet som ska kontrolleras. |

### Returvärde

True om presentationen är skrivskyddad och lösenordet är korrekt. False annars.

## Anmärkningar

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. Du bör kontrollera egenskapen [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) innan du anropar den här metoden.
1. När lösenordet är null eller tomt, returnerar den här metoden false.

## Se även

* Klass [String](../../../system/string/)
* Klass [IPresentationInfo](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)