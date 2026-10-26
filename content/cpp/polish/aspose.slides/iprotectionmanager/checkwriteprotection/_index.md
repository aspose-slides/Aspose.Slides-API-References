---
title: CheckWriteProtection()
second_title: Referencja API Aspose.Slides dla C++
description: Określa, czy prezentacja jest zabezpieczona hasłem przed modyfikacją.
type: docs
weight: 157
url: /pl/aspose.slides/iprotectionmanager/checkwriteprotection/
---
## IProtectionManager::CheckWriteProtection(System::String) metoda

Określa, czy prezentacja jest zabezpieczona hasłem przed modyfikacją.

```cpp
virtual bool Aspose::Slides::IProtectionManager::CheckWriteProtection(System::String password)=0
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Hasło do sprawdzenia. |

### Wartość zwracana

True jeśli hasło jest prawidłowe; w przeciwnym razie false.

## Uwagi

```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```

1. Należy sprawdzić właściwość [IProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) przed wywołaniem tej metody.
1. Gdy hasło jest null lub puste, ta metoda zwraca false.

## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IProtectionManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)