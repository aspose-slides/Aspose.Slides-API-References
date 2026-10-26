---
title: CheckWriteProtection()
second_title: Aspose.Slides dla C++ – odwołanie API
description: Sprawdza, czy hasło do modyfikacji jest poprawne dla zabezpieczonej przed zapisem prezentacji.
type: docs
weight: 66
url: /pl/aspose.slides/ipresentationinfo/checkwriteprotection/
---
## IPresentationInfo::CheckWriteProtection(System::String) metoda

Sprawdza, czy hasło do modyfikacji jest poprawne dla prezentacji zabezpieczonej przed zapisem.

```cpp
virtual bool Aspose::Slides::IPresentationInfo::CheckWriteProtection(System::String password)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Hasło do sprawdzenia. |

### Wartość zwracana

True, jeśli prezentacja jest zabezpieczona przed zapisem i hasło jest poprawne. False w przeciwnym razie.

## Uwagi

```cpp
auto info = PresentationFactory::get_Instance()->GetPresentationInfo(presentationFilePath);
if (info->get_IsWriteProtected() == NullableBool::True)
{
    bool isWriteProtectedByPassword = info->CheckWriteProtection(u"my_password");
}
```

1. Należy sprawdzić właściwość [IPresentationInfo::get_IsWriteProtected](../get_iswriteprotected/) przed wywołaniem tej metody.
1. Gdy hasło jest null lub puste, ta metoda zwraca false.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IPresentationInfo](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)