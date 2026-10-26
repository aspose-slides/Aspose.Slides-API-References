---
title: get_IsWriteProtected()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Zwraca wartość wskazującą, czy powiązana prezentacja jest zabezpieczona przed zapisem.
type: docs
weight: 27
url: /pl/aspose.slides/presentationinfo/get_iswriteprotected/
---
## PresentationInfo::get_IsWriteProtected() metoda

Zwraca wartość wskazującą, czy powiązana prezentacja jest zabezpieczona przed zapisem.

```cpp
NullableBool Aspose::Slides::PresentationInfo::get_IsWriteProtected() override
```

## Uwagi



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Jeśli prezentacja jest zabezpieczona hasłem do otwarcia, wartość właściwości równa się NotDefined. 
## Zobacz także

* Wyliczenie [NullableBool](../../nullablebool/)
* Klasa [PresentationInfo](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)