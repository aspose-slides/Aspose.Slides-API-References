---
title: CheckWriteProtection()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Określa, czy prezentacja jest chroniona hasłem przed modyfikacją.
type: docs
weight: 157
url: /pl/aspose.slides/protectionmanager/checkwriteprotection/
---
## ProtectionManager::CheckWriteProtection(System::String) metoda


Określa, czy prezentacja jest chroniona hasłem przed modyfikacją.

```cpp
bool Aspose::Slides::ProtectionManager::CheckWriteProtection(System::String password) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| password | [System::String](../../../system/string/) | Hasło używane do sprawdzenia. |

### Wartość zwracana

True jeśli hasło jest prawidłowe; w przeciwnym razie false.
## Uwagi



```cpp
auto presentation = System::MakeObject<Presentation>(presentationFilePath);
bool isWriteProtected = presentation->get_ProtectionManager()->CheckWriteProtection(u"my_password");
```



1. Należy sprawdzić właściwość [ProtectionManager::get_IsWriteProtected](../get_iswriteprotected/) przed wywołaniem tej metody.
1. Gdy hasło jest równe null lub puste, metoda zwraca false.


## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [ProtectionManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)