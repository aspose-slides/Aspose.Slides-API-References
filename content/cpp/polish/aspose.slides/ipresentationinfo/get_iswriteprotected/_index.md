---
title: get_IsWriteProtected()
second_title: Odwołanie API Aspose.Slides dla C++
description: Zwraca wartość wskazującą, czy powiązana prezentacja jest zabezpieczona przed zapisem.
type: docs
weight: 27
url: /pl/aspose.slides/ipresentationinfo/get_iswriteprotected/
---
## IPresentationInfo::get_IsWriteProtected() metoda

Zwraca wartość wskazującą, czy powiązana prezentacja jest zabezpieczona przed zapisem.

```cpp
virtual NullableBool Aspose::Slides::IPresentationInfo::get_IsWriteProtected()=0
```

## Uwagi



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    System::Console::WriteLine(System::String(u"The presentation '") + presentationFilePath + u"' is write protected by a password.");
}
```


Jeśli prezentacja jest zabezpieczona hasłem do otwarcia, wartość właściwości jest równa NotDefined. Zobacz enumerację [NullableBool](../../nullablebool/). 
## Zobacz także

* Wyliczenie [NullableBool](../../nullablebool/)
* Klasa [IPresentationInfo](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)