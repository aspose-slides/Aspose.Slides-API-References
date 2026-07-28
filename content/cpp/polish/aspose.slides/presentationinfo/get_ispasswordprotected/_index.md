---
title: get_IsPasswordProtected()
second_title: Aspose.Slides for C++ Referencja API
description: Zwraca wartość wskazującą, czy powiązana prezentacja jest chroniona hasłem przy otwieraniu.
type: docs
weight: 14
url: /pl/aspose.slides/presentationinfo/get_ispasswordprotected/
---
## PresentationInfo::get_IsPasswordProtected() metoda


Zwraca wartość wskazującą, czy powiązana prezentacja jest chroniona hasłem przy otwieraniu.

```cpp
bool Aspose::Slides::PresentationInfo::get_IsPasswordProtected() override
```

## Uwagi



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsPasswordProtected())
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is protected by password to open.");
}
```

## Zobacz także

* Klasa [PresentationInfo](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)