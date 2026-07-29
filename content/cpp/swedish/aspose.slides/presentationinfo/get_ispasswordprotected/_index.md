---
title: get_IsPasswordProtected()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar ett värde som indikerar om en bunden presentation är skyddad med ett lösenord för att öppna.
type: docs
weight: 14
url: /sv/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() metod


Hämtar ett värde som indikerar om en bunden presentation är skyddad med ett lösenord för att öppna.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## Anmärkningar



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## Se också

* Klass [PresentationInfo](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)