---
title: CheckWriteProtection()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Sprawdza, czy hasło służące do modyfikacji jest prawidłowe dla prezentacji chronionej przed zapisem.
type: docs
weight: 66
url: /pl/aspose.slides/presentationinfo/checkwriteprotection/
---
## PresentationInfo::CheckWriteProtection(System::String) metoda


Sprawdza, czy hasło do modyfikacji jest prawidłowe dla prezentacji chronionej przed zapisem.

```cpp
bool Aspose::Slides::PresentationInfo::CheckWriteProtection(System::String password) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Hasło do sprawdzenia. |

### Wartość zwracana

True jeśli prezentacja jest chroniona przed zapisem i hasło jest prawidłowe. False w przeciwnym razie.
## Uwagi



```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```



1. Należy sprawdzić właściwość [PresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) przed wywołaniem tej metody.
1. Gdy hasło jest null lub puste, ta metoda zwraca false.



## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [PresentationInfo](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)