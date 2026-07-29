---
title: get_IsPasswordProtected()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar ett värde som indikerar om en bunden presentation är skyddad med ett lösenord för att öppnas.
type: docs
weight: 14
url: /sv/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() metod


Hämtar ett värde som indikerar om en bunden presentation är skyddad med ett lösenord för att öppnas.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Anmärkningar



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## Se även

* Klass [IPresentationInfo](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)