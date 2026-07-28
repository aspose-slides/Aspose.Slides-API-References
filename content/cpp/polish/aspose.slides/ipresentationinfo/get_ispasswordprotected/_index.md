--- 
title: get_IsPasswordProtected()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Zwraca wartość określającą, czy powiązana prezentacja jest chroniona hasłem przy otwieraniu.
type: docs
weight: 14
url: /pl/aspose.slides/ipresentationinfo/get_ispasswordprotected/
---
## IPresentationInfo::get_IsPasswordProtected() metoda


Zwraca wartość wskazującą, czy powiązana prezentacja jest chroniona hasłem przy otwieraniu.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::get_IsPasswordProtected()=0
```

## Uwagi



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by a password to open.");
}
```

## Zobacz także

* Klasa [IPresentationInfo](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)